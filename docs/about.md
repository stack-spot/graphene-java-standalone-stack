## graphene-java-standalone-stack
Create Java applications or modules in a standardized and fast way;

The stack enables you to choose between one of the Java versions (11 or 17),
in addition to enabling selecting one of the build tools (Gradle or Maven),
or even generating a Java project without the build tool.

Ideally, the stack enables you to create experiments, concepts validation, tests and algorithms in an easy, intuitive
and fast way 

#### See below some use examples that the stack can be useful
- POC
- Java Experiments
- Tests
- Algorithms
- Java application modules.

#### **Requirements**
- [**CLI StakSpot Installation**](https://docs.stackspot.com/latest/os-cli/installation/)
- [**Java >= 11**](https://openjdk.org/)
- [**Git**](https://git-scm.com/)

- ##### 1. Execute the command below after the stack had been imported:
 ```bash
    stk create app <nome da aplicação> --template graphene-java-standalone-stack/starter-java
 ```
- ##### 2. Enter with the as-is shown below:
- Project Version
- Package Name: E.g (br.com.orgname)
- Java version: (11 or 17)
- Build Tool: (Maven, Gradle ou None)

- ##### 3. Make the project build
- Go to the generated project root, and execute one of the commands below according to the inputted information
- Make the application build through **Gradle or Maven**. E.g
  - Linux
      ```bash
      #Maven:
        ./mvnw clean install
      #OR Gradle
        ./gradlew build
      ```
  - Windows
      ```bash
      #Maven: 
          mvnw clean install**
      #OR Gradle: 
          gradlew build
      ``` 

