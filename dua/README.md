# Projeto
> API responsável por acessar a base `due` e gerenciar seus dados.

> Base `dua`
- PostgreSQL (DynamoDB);
- Todos os dados armazenados nesta base de dados é criptografado com xxx
e só poder ser acessado pela API `dua`;
- Apenas a API `dua` possue a chave de criptografia;

Tabelas:

| Person (Pessoa) |
|--------|
| id |
| age |
| address |

| Income (Fontes de renda) |
|--------|
| id |
| person_id |
| description |
| value |

# Tecnologias
- Kotlin (Java 11)
- Gradle
- Spring boot coroutines
- Hibernate
- Hikari
- Flyway