## **Caso de Uso**
Este Caso de Uso é ideal para a inicialização de projetos Java 17 com Maven

### **Visão Geral**
Possibilita a criação de aplicações Java 17 utilizando Maven de forma rápida com execução de um simples comando.

### **Pré-requisitos**
Para usar a stack/template é preciso ter instalado os itens abaixo:

- [**Instalação StakSpot CLI**](https://docs.stackspot.com/latest/os-cli/installation/)
- [**Java 17**](https://openjdk.org/)
- [**Git**](https://git-scm.com/)

### Configuração Stack CLI
- ##### 1 Execute o comando abaixo para atualizar o catalogo de studios
 ```bash
    stk import stack https://github.com/stack-spot/graphene-java-standalone-stack
 ```
**Listagem template disponíveis localmente:**
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

### Instalacao
Para criar uma aplicação e já configurar o seu projeto com o Maven a Java 17, copie e cole o comando abaixo no seu terminal:

```bash
stk create app meu-teste-app --stackfile graphene-java-standalone-stack/maven-java-17
```
