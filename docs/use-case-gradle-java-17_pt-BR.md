## **Caso de Uso**
Este caso de uso é ideal para a inicialização de projetos Java 17 com Gradle.

### **Visão Geral**
Você pode criar aplicações Java 17 utilizando Gradle de forma rápida, executando apenas um comando.

### **Pré-requisitos**
Para usar a stack/template é preciso ter instalado os itens abaixo:

- [**STK CLI**](https://stackspot.com/login?route=/download/cli)
- [**Java 17**](https://openjdk.org/)
- [**Git**](https://git-scm.com/)

### Configuração da Stack
Siga os passos abaixo:
**Passo 1.** Listar os template disponíveis localmente
```bash
stk list template
```
**Exemplo output:**
```bash
Stack: graphene-java-standalone-stack
+-------------------------+-----------------------------------------------------------+------------------+-----------------+
| name                    | description                                                | types            | version(latest) |
+-------------------------+------------------------------------------------------------+------------------+-----------------+
|    java-starter         | Template usado para facilitar a criação de projetos Java,  | ['app-template'] | no release      |
|                         | possibilitando escolher entre suas versões, bem como  a    |                  |                 |
|                         | ferramenta de build de sua escolha (Gradle, Maven),        |                  |                 |
|                         | realizar experimentos, validações de conceitos, testes e   |                  |                 |
|                         | algoritmos.                                                |                  |                 |
+-------------------------+-----------------------------------------------------------+------------------+------------------+
```

### Instalação
Para criar uma aplicação e configurar o seu projeto com o Gradle a Java 17, execute o comando abaixo no seu terminal:

```bash
stk create app meu-teste-app --stackfile graphene-java-standalone-stack/gradle-java-17
```
