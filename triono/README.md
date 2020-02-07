# Projeto
> API responsável por acessar a base `triono` e gerenciar seus dados.

### Base `triono`
- MongoDB

Documentos:

| Aggregation (Dados acumulados) |
|--------|
| last_document_consultation |
| last_amount_paid_on_the_card |

| financial (Movimentações financeiras) |
|--------|
| id |
| date_at |
| description |
| value |

### Tecnologias
- Kotlin (Java 11)
- Gradle
- Ktor
- Exposed (ORM)