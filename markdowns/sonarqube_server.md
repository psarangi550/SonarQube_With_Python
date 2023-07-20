# <ins> Sonarqube Server Visits </ins> #

- the default port for the `sonarqube saerver` the port on `9000`

- we can login to the `sonarqube server` by clicking on the `sonarqube server login`

    - the default username and password for the `sonarqube server` is of 

        - username:`admin` and password:`admin`

- we can change that by going to the `Administrator` &rarr; `security` where we can create the 

    - new user
    - new groups


- The `webUi` has the below details such as 
  
  - projects where we can see 

    - `Bugs`
    - `Vulnerablity`
    - `code-smell`
    - `coverage`
    - `Duplication`

- from the `left` we can filter out which of the `projects` which is `getting passed` or `warning` or `Failed` stages

- from the `top` we can define what params we want to see such as 
  
  - `Overall Status`
  - `Risks`
  - `code-coverage`
  - `Duplication`
  - `Maintainablity`
  - `Reliabilty`
  - `Security`

- we can also sort based on the 
  
  - Name
  - Reliabilty
  - Security
  - Coverage
  - Duplication
  - Size
  - Maintainablity

- we can go into to the `project` and then it will show below info such as 
  
  - number of `Bugs` and `Vulnerablities` based on the `preveiosu version on the left` and `new version on the right`
  - similarly number of `code-smell or coverage or Duplication ` based on the `preveiosu version on the left` and `new version on the right`
  - we can also see the `List of Issues` present inside thje code
  - `security report based on different standards` which can be configured as `Quality Profile`
  - we can also see the `code measure`
  - we can also see the `Source code` as well
  - on the `source code` we can do the &darr; we can see the below details such as 
    - what type of issue that one is
    - whether minor/major issue
    - the status of the `issue` whether `closed` or `open` and even assign a `sonarqube user` for the same
    - it will show how much `effort` then how much time it will going to Take
    - on the `Activity` we can see the `Number of Build` thats been happening

- we can generate the build on the base of `sonar-scanner.bat` fiole in `windows`
- when we use the `sonar-scanner.bat` which will generate a new `build` in the `Activity section` using which we can see the 
  - `code-smell`
  - `vulnerabilities`
  - `bugs`
  - `coverage`
  - `Duplication`

- if we want we can also mark the `signifact build with the number as well` which will be known as the `Event`

- we also have to use the `sonar.properties` file which will help in update the `keys` present in the `Administration Section`

- on the `sonar.properties` we can define below paramets as `key=value` format

    - `sonar.host.url`=`http://localhost:9000`
    - `sonar.sourceEncoding`=`UTF-8`
    - `sonar.projectKey`=`<name of the project>`
    - `sonar.projectName`=`Name of the Project`
    - `sonar.projectVersion`=`1.0`
    - `sonar.scm.disabled`=`True`
    - `sonar.sources`=`base location of the code`
    - `sonar.language`=`<language we want to Test>`

- we can delete the `Project` then we can go to the `Administration` &rarr; `Delete Project`

- we can change the `general setting` we can go to the `Administration` &rarr; `General Setting`

- if we have the `specific Quality Profile` for the `Project` then we can set it using the `quality profile` in the `Administration Section` otherwise it will take the default one

- we can also set the `Permission` we can provide in the `Administration` &rarr; `Permission`

- on the `global level` for all the `projects` we have

    - `Projects`
    - `Issue`
    - `Rules`
    - `Quality Profile`
    - `Quality Gates`
    - `Administration`

- the `Rules` which define what `Rules` we have `different type of project based on the Languages` which can be changed
- the `Quality Profile` when we are ouside show the `Default Quality profile` that been set for all languages





