<br>
<h1 align="center">
API para Gerenciamento de Pessoas 👨‍👩‍👧‍👧
</h1>
<br>

## 💬 Sobre o repositório

API desenvolvida para um sistema de gerenciamento de pessoas, utilizando Java 11, Spring Boot, Maven e Heroku.

## 📑 Tópicos abordados

* Setup inicial de projeto com o Spring Boot Initialzr
* Criação de [modelo de dados](https://ibb.co/y8tr0GX) para o mapeamento de entidades em bancos de dados
* Desenvolvimento de operações de gerenciamento de usuários (Cadastro, leitura, atualização e remoção de pessoas de um sistema)
* Relação de cada uma das operações acima com o padrão arquitetural REST (GET, POST, PUT, DELETE)
* Desenvolvimento de testes unitários para validação das funcionalidades (JUnit)
* Deploy do projeto na nuvem através do Heroku

## 📌 Como utilizar?

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/people
```

Para conferir se as operações de gerenciamento de usuários estão funcionando, utilize o Postman, [clique aqui para ver!](https://ibb.co/0QMytWZ)

## ⚠ Pré-requisitos para execução do projeto

* Java 11 ou versões superiores
* Maven 3.8.2 ou versões superiores

## 🧠 Links importantes

* [Documentação oficial do Lombok](https://projectlombok.org/)
* [Documentação oficial do Map Struct](https://mapstruct.org/)
* [Referência para o padrão arquitetural REST](https://restfulapi.net/)
* [Palheta de atalhos de comandos do IntelliJ](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Site oficial do Spring](https://spring.io/)
* [Site oficial do Spring Initialzr para setup do projeto](https://start.spring.io/)
* [SDKMan! para gerenciamento e instalação do Java e Maven](https://sdkman.io/)

---
