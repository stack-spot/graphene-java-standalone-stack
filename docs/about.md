## graphene-java-standalone-stack
Create standardized Java applications or modules in a fast way;

The stack allows you to choose between two Java versions: 11 or 17. You can select one build tool Gradle or Maven,
or even generate a Java project without a build tool.

Ideally, the stack enables you to create experiments, concepts validation, tests and algorithms in an easy, intuitive
and fast way 

#### See some use examples where stacks can be useful:
- Proof Of Concept (POC)
- Java Experiments
- Tests
- Algorithms
- Java application modules.

#### **Requirements**
- [**STK CLI**](https://stackspot.com/login?route=/download/cli)
- [**Java >= 11**](https://openjdk.org/)
- [**Git**](https://git-scm.com/)

Follow the steps below:
- ##### Step 1. Create your application
Execute the command below:
 ```bash
    stk create app <nome da aplicação> --template graphene-java-standalone-stack/starter-java
 ```
- ##### Step 2. Add the inputs
See below:
- Project Version.
- Package Name: E.g (br.com.orgname).
- Java version: (11 or 17).
- Build Tool: (Maven, Gradle, or None).

- ##### 3. Build the project
Go to the generated project root, and execute one of the commands below according to the selected build tool.
Build the application through **Gradle or Maven**. See the example:
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

