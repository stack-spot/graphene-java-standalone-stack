## **Caso de Uso**
This use case is ideal to initialize projects using Java 17 with Maven

### **Overview**
Enables the creation of projects using Java 17 and Maven quickly through the execution of a simple command.

### **Requirements**
- [**CLI StakSpot Installation**](https://docs.stackspot.com/latest/os-cli/installation/)
- [**Java 17**](https://openjdk.org/)
- [**Git**](https://git-scm.com/)

### Configuring stack
- ##### 1 Execute the command below to make the stack importation
 ```bash
    stk import stack https://github.com/stack-spot/graphene-java-standalone-stack
 ```
**List available templates locally:**
```bash
stk list template
```
**Output example:**
```bash
Stack: graphene-java-standalone-stack
+-------------------------+-------------------------------------------------------------+------------------+-----------------+
| name                    | description                                                 | types            | version(latest) |
+-------------------------+------------------------------------------------------------ +------------------+-----------------+
|    java-starter         | Template used to simplify the Java project creation,        | ['app-template'] | no release      |
|                         | enabling to choose between its versions, as well as         |                  |                 |
|                         | the build tool according to your preference (Gradle, Maven),|                  |                 |
|                         | making experiments, concepts validation, tests and fast     |                  |                 |
|                         | algorithms creation.                                        |                  |                 |
+-------------------------+-----------------------------------------------------------+-------------------+------------------+
```

### Installation
Copy and execute the command below to create a fast application using Java 17 and Maven:

```bash
stk create app meu-teste-app --stackfile graphene-java-standalone-stack/maven-java-17
```
