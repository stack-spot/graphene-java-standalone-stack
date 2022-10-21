## graphene-java-standalone-stack
Crie aplicações ou módulo Java de forma rápida e padronizada;

A stack permite que você escolha entre as versões (11 or 17) do Java,
além de permitir selecionar uma das ferramentas de build (Gradle ou Maven),
ou até mesmo gerar um projeto Java puro, sem ferramentas de build.

Realize experimentos, validações de conceitos, testes e algoritmos de forma rápida e intuitiva.

#### Veja abaixo os cenários de exemplos em que a utilização da stack é aplicável:
- POC
- Experimentos Java
- Testes
- Algoritmos
- Módulos de aplicações Java.

#### **Pré-requisitos**
- [**Instalação StakSpot CLI**](https://docs.stackspot.com/latest/os-cli/installation/)
- [**Java >= 11**](https://openjdk.org/)
- [**Git**](https://git-scm.com/)

- ##### 1. Após a importação da stack, executar o comando abaixo
 ```bash
    stk create app <nome da aplicação> --template graphene-java-standalone-stack/starter-java
 ```

- ##### 2 Realizar o preenchimento dos inputs solicitados conforme mostrado abaixo:
- Versão do projeto
- Nome do pacote: Ex (br.com.orgname)
- Versão do Java: (11 ou 17)
- Ferramenta de Build: (Maven, Gradle ou None)

- ##### 3 Realizar o build do projeto
- Navegar até a raiz do projeto gerado e executar um dos comandos abaixo de acordo com o preenchimento dos inputs
- Realizar o build da aplicação através do **gradle ou maven**. Ex:
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
