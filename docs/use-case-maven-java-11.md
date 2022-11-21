## **Caso de Uso**
This use case is ideal to initialize projects using Java 11 with Maven

### **Overview**
You can create projects using Java 11 and Maven with one command.

### **Requirements**
- [**STK CLI**](https://stackspot.com/login?route=/download/cli)
- [**Java 11**](https://openjdk.org/)
- [**Git**](https://git-scm.com/)

### Configure a Stack
Follow the steps below:
**Step 1.** List available templates locally:
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
|                         | the build tool according to your preference (Gradle, Maven).|                  |                 |
|                         | You can make experiments, concepts validation, tests, and   |                  |                 |
|                         | fast algorithms creation.                                   |                  |                 |
+-------------------------+-----------------------------------------------------------+-------------------+------------------+
```

### Installation
To create a fast application using Java 11 and Maven, execute the command in the terminal:

```bash
stk create app meu-teste-app --stackfile graphene-java-standalone-stack/maven-java-11
```
