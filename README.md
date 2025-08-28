
# Projeto Board JDBC

Projeto Java para gerenciamento de quadros, colunas e cartões, utilizando JDBC e banco de dados MySQL.

## Pré-requisitos

- Java 17+ (de preferência 23)
- Maven
- Docker

## Banco de Dados

Para rodar o projeto, é necessário subir um container MySQL com o seguinte comando:

```sh
docker run --name projetoJDBC -e MYSQL_ROOT_PASSWORD=123 -e MYSQL_DATABASE=board -p 3306:3306 -d mysql:8.0
```

O banco será criado automaticamente com o nome `board` e senha do root `123`.

## Como rodar

1. Suba o container do banco de dados conforme acima.
2. Execute o projeto via Maven ou pela sua IDE.

## Estrutura

- Código-fonte: `src/main/java`
- Scripts SQL e migrações: `src/main/resources/db/changelog`
