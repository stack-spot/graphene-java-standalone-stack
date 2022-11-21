## graphene-java-standalone-stack
Crie aplicações ou módulo Java de forma rápida e padronizada;

A stack permite você escolher entre as versões (11 or 17) do Java, além de selecionar uma das ferramentas de build Gradle ou Maven,
ou até mesmo gerar um projeto Java sem ferramentas de build.

Realize experimentos, validações de conceitos, testes e algoritmos de forma rápida e intuitiva.

#### Veja abaixo os cenários de exemplos em que a utilização da stack é aplicável:
- Prova de Conceitos (POC)
- Experimentos Java
- Testes
- Algoritmos
- Módulos de aplicações Java.

#### **Pré-requisitos**
- [**Instalação STK CLI**](https://stackspot.com/login?route=/download/cli)
- [**Java >= 11**](https://openjdk.org/)
- [**Git**](https://git-scm.com/)

Siga os passos abaixo:
- ##### Passo 1. Criar sua aplicação
Execute o comando abaixo:
 ```bash
    stk create app <nome da aplicação> --template graphene-java-standalone-stack/starter-java
 ```
- ##### Passo 2. Preencher os inputs
Confira abaixo:
- Versão do projeto
- Nome do pacote: Ex (br.com.orgname)
- Versão do Java: (11 ou 17)
- Ferramenta de Build: (Maven, Gradle ou None)

- ##### Passo 3. Realizar o build do projeto
Navegue até a raiz do projeto gerado e execute um dos comandos abaixo de acordo com a ferramenta de build escolhida.
Depois faça o build da aplicação por meio do **gradle ou maven**. Confira o exemplo:
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
