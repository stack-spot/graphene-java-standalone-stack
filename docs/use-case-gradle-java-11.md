## **Use case**
This use case initializes projects using Java 11 with Gradle.

### **Overview**
This example shows how to quickly create projects using Java 11 and Gradle executing a simple command.

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
Copy and execute the command below to create a fast application using Java 11 and Gradle:

```bash
stk create app meu-teste-app --stackfile graphene-java-standalone-stack/gradle-java-11
```
