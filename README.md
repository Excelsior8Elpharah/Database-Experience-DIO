# Database-Experience-DIO
Desafio: Compreendendo o Papel de Bancos de Dados Relacionais e Não Relacionais no Contexto de Engenharia de Dados

"SQL_vs_NoSQL_Engenharia_de_Dados"

# SQL vs NoSQL: Papel na Engenharia de Dados

Este repositório explora o papel de Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de Engenharia de Dados. Inclui conceitos, exemplos práticos e comparações para ajudar profissionais a escolher a abordagem certa em diferentes cenários.

## 📚 Organização do Repositório
1. **SQL/**: Introdução e exemplos práticos de SQL.
2. **NoSQL/**: Introdução e exemplos práticos de bancos NoSQL.
3. **Comparacao/**: Diferenças fundamentais e critérios para escolher entre SQL e NoSQL.

---

## 🚀 Conceitos Relevantes

### Bancos de Dados Relacionais (SQL)
- Seguem o modelo relacional: dados estruturados em tabelas.
- Usam **SQL (Structured Query Language)** para manipulação de dados.
- Garantem:
  - **Integridade referencial**.
  - **Transações ACID** (Atomicidade, Consistência, Isolamento, Durabilidade).
- Exemplos: MySQL, PostgreSQL, Oracle DB.

### Bancos de Dados Não Relacionais (NoSQL)
- Estruturados em diferentes modelos: **Documentos**, **Chaves-Valor**, **Colunas** ou **Grafos**.
- Mais flexíveis, permitindo esquemas dinâmicos.
- Escalabilidade horizontal.
- Exemplos: MongoDB, Cassandra, Redis, Neo4j.

---

## 🔄 Diferenças entre SQL e NoSQL

| Aspecto              | SQL                          | NoSQL                       |
|----------------------|------------------------------|-----------------------------|
| **Estrutura**        | Tabelas                     | Documentos, Grafos, etc.    |
| **Escalabilidade**   | Vertical                    | Horizontal                  |
| **Esquema**          | Rígido                      | Flexível                    |
| **Transações**       | ACID                        | BASE (Eventual Consistency) |
| **Casos de Uso**     | Dados estruturados          | Dados dinâmicos e massivos  |

---

## 🎯 Casos de Uso
- **SQL**:
  - Sistemas bancários.
  - ERP e CRM.
- **NoSQL**:
  - Sistemas de recomendação.
  - Aplicações IoT.
  - Redes sociais.

---

## 🔧 Exemplos Práticos
- **SQL**:
  ```sql
  SELECT * FROM clientes WHERE idade > 30;
  
NoSQL (MongoDB):

json

db.clientes.find({ "idade": { "$gt": 30 } });

https://dev.mysql.com/doc/
https://www.mongodb.com/pt-br/docs/

