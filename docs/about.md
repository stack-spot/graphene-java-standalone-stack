## graphene-java-standalone-stack
Crie aplicações ou módulo Java de forma rápida e padronizada;

Escolha entre as versões do Java (11 e 17);

Defina entre as ferramentas de build (Gradle, Maven), ou até mesmo crie um projeto para ser compilado e executado de forma nativa, sem a utilização ferramentas auxiliares, conforme a sua necessidade;

Realize experimentos, validações de conceitos, testes e algoritmos de forma rápida e intuitiva.

#### Veja abaixo os cenários de exemplos em que a utilização da stack é aplicável:
- Poc
- Experimentos Java
- Testes
- Algoritmos
- Módulos de aplicações Java.

#### Para utilizar o template standalone é necessário realizar os seguintes passos:
- ##### 1 Importar a stack
 ```
    stk import stack https://github.com/stack-spot/graphene-java-standalone-stack
 ```

- ##### 2 Executar o comando
 ```
    stk create app <nome da aplicação> --template graphene-java-standalone-stack/starter-java
 ```

#### O stackspot irá solicitar o preenchimento dos seguintes inputs:
- Versão do projeto
- Nome do pacote: Ex (br.com.orgname)
- Versão do Java: (11 ou 17)
- Ferramenta de compilação: (Maven, Gradle ou None)

### Requerimentos:
- É necessário ter o Java instalado no ambiente conforme com a versão selecionada durante a geração do projeto.
- Gradle ou Maven previamente configurado, ou utilizar os wrappers gerados na raiz do projeto.
  - Realização do build da aplicação utilizando os wrappers. Ex:
    - Linux
      - Maven: **./mvnw clean install**
      - Gradle: **./gradlew build**
    - Windows
      - Maven: **mvnw clean install**
      - Gradle: **gradlew build**