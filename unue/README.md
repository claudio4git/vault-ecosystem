# Projeto
> API responsável por acessar a base `unue` e gerenciar seus dados.

# Base `unue`
- PostgreSQL (DynamoDB);
- Todos os dados armazenados nesta base de dados é criptografado com xxx
e só poder ser acessado pela API `unue`;
- Apenas a API `unue` possue a chave de criptografia;

Tabelas:

| Person (Pessoa) |
|--------|
| id |
| document |
| name |
| address |

| Debt (Dívidas) |
|--------|
| id |
| person_id |
| description |
| value |

# Tecnologias
- Kotlin (Java 11)
- Gradle
- Spring boot
- Hibernate
- Hikari
- Flyway