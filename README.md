# API REST

## Tecnologias utilizadas
- Java 16
- Spring Boot
- Spring Data JPA
- MapStruct
- Project Lombok
- H2 Database
- Git

## Descrição da API
A API permite o cadastro (POST), update (PUT), consultas (GET) e remoções (DELETE) de pessoas do sistema, armazenadas em um bando de dados em memória.
O cadastro de pessoas é compostos pelos campos Id, nome, sobrenome, CPF, data de nascimento e telefones.
O cadastro de telefones é composto pelos campos Id, tipo e número.
O relacionamento de pessoas com telefones é de um para muitos.
O banco é composto por 3 tabelas, uma de pessoas, uma de telefones e uma tabela intermediária relacionando os Id's de pessoas e telefones.

Após executar o projeto, basta apenas abrir o seguinte endereço e visualizar a execução da aplicação:

**http://localhost:8080/api/v1/people**

Deploy também feito na nuvem na plataforma heroku.
