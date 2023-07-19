# <ins> SonarQube Basic Tutorial </ins> #

- sonarqube perform `continious code inspection and analysis` 

- there werte various `feature and functionality been provided by sonarqube` such as :-

  - support various rules 
  - support for the issues
  - support quality gates
  - support quality profile
  - administration of sonarqube

- we will also learn about the `sonar scanner` and `How to integrate that with ` build tool like 
  
  - maven
  - gradel
  - Ant 
  - jenkins
  - MS Build
  
- how to use the `sonar lint` which can be integrated with `IDE` such as `Eclipse` provide `real time analusis of the code`

# <ins> Architecture of SonarQube </ins> #

- there are 3 major component of `sonar qube`

  - scanner
  - server
  - Database

- `sonarqube` have a `builtin db` which can be used for the `test purpose` otherwise we can also integrate `DBs` such as 

  - postgres db
  - MySQL db
  - MS SQL
  - oracle

- it can store various info such as 
  
  - quality snapshots
  - views
  - rules
  - gateway
  - etc 

- `sonarqube` have `standalone scanner` , it `sonar scanner` get the `report` from the `code` and save that to the `sonar server` 

- sonarqube `server` is the `heart of the Sonarqube` which consist of 3 parts

  - compute Engine
  - Search Server which is a `ElastiocSearch` server
  -  webserver which can be modified by adding `n number of plugins`

- **compute Engine**:- 

  - compute Engine going to take `report` from the `sonar sacanner` then `digest` them and `analyze` them and then `Store that to the Database`

- **search server** :-
  
  - `search server` will help in getting the result and display that onto the screen and save it as a `report` showing 

    - when the `vernerbility` lies
    - detect the `code smell` and `defect` in it

  - this sends the `result` to the `web UI` where user can view the `quality snapshots`

- **webserver**

  - which provide a `web UI` which will show `for the project where the vulnerablity is or where the code smell is or where the defect is there`

  - it can also help in configuraing the `sonarqube` instance in here

  - for the `developer` or `manager` provide `quality snapshots`



- 


