# Qry_Oracle

> Repositório dedicado ao estudo, organização e compartilhamento de consultas SQL e recursos do Oracle Database.

---

# Objetivos

Este repositório tem como finalidade:

- Centralizar consultas SQL Oracle
- Compartilhar exemplos práticos
- Documentar boas práticas
- Servir como material de estudo
- Facilitar consultas recorrentes
- Auxiliar em otimização de desempenho

---

# Público-alvo

- DBAs
- Desenvolvedores SQL
- Engenheiros de Dados
- Analistas de Dados
- Administradores Oracle
- Estudantes

---

# Conteúdo

## SQL Básico

- SELECT
- WHERE
- DISTINCT
- ORDER BY
- GROUP BY
- HAVING
- FETCH FIRST
- OFFSET

---

## JOINs

- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL OUTER JOIN
- CROSS JOIN
- SELF JOIN

---

## Subconsultas

- Subquery Simples
- Correlated Subquery
- EXISTS
- NOT EXISTS
- IN
- NOT IN
- ANY
- ALL

---

## Common Table Expressions (CTE)

- WITH
- Recursive CTE

---

## Funções Oracle

### Conversão

- TO_DATE
- TO_CHAR
- TO_NUMBER
- CAST
- CONVERT

### Texto

- SUBSTR
- INSTR
- REPLACE
- TRANSLATE
- UPPER
- LOWER
- INITCAP
- TRIM
- LPAD
- RPAD

### Numéricas

- ROUND
- TRUNC
- MOD
- CEIL
- FLOOR
- ABS

### Datas

- SYSDATE
- CURRENT_DATE
- ADD_MONTHS
- LAST_DAY
- NEXT_DAY
- MONTHS_BETWEEN
- EXTRACT

### Condicionais

- CASE
- DECODE
- NVL
- NVL2
- COALESCE
- NULLIF

---

# Window Functions

- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- LEAD()
- LAG()
- FIRST_VALUE()
- LAST_VALUE()
- SUM OVER()
- AVG OVER()

---

# Agregações

- COUNT
- SUM
- AVG
- MAX
- MIN
- LISTAGG

---

# Expressões Regulares

- REGEXP_LIKE
- REGEXP_SUBSTR
- REGEXP_REPLACE
- REGEXP_COUNT
- REGEXP_INSTR

---

# Manipulação JSON

- JSON_OBJECT
- JSON_ARRAY
- JSON_VALUE
- JSON_QUERY
- JSON_TABLE

---

# XML

- XMLTABLE
- XMLTYPE
- EXTRACTVALUE
- XMLQUERY

---

# PL/SQL

- Blocos Anônimos
- Procedures
- Functions
- Packages
- Triggers
- Exceptions
- Cursores
- Collections

---

# DDL

- CREATE
- ALTER
- DROP
- TRUNCATE
- RENAME
- COMMENT

---

# DML

- INSERT
- UPDATE
- DELETE
- MERGE

---

# TCL

- COMMIT
- ROLLBACK
- SAVEPOINT

---

# DCL

- GRANT
- REVOKE

---

# Administração

- Usuários
- Roles
- Tablespaces
- Profiles
- Sequences
- Synonyms
- Database Links

---

# Objetos Oracle

- Tables
- Views
- Materialized Views
- Indexes
- Constraints
- Sequences
- Synonyms

---

# Performance

- Explain Plan
- Autotrace
- SQL Trace
- TKPROF
- Hints
- Gather Statistics
- Parallel Query

---

# Índices

- B-Tree
- Bitmap
- Function Based Index
- Composite Index

---

# Particionamento

- Range
- List
- Hash
- Interval
- Composite

---

# Oracle Data Dictionary

Consultas nas principais visões:

- USER_TABLES
- ALL_TABLES
- DBA_TABLES
- USER_OBJECTS
- ALL_OBJECTS
- DBA_OBJECTS
- USER_TAB_COLUMNS
- ALL_CONSTRAINTS
- DBA_INDEXES

---

# Administração de Sessões

- V$SESSION
- V$SQL
- V$LOCK
- V$PROCESS
- V$INSTANCE
- V$DATABASE

---

# Backup e Recovery

- RMAN
- Flashback
- Data Pump
- Export
- Import

---

# Segurança

- Roles
- Privilégios
- Auditoria
- Transparent Data Encryption
- Oracle Wallet

---

# Estrutura Recomendada

```
Qry_Oracle
│
├── README.md
│
├── SQL
│   ├── SELECT
│   ├── JOIN
│   ├── GROUP_BY
│   ├── WINDOW_FUNCTIONS
│   ├── JSON
│   ├── XML
│   ├── PERFORMANCE
│   └── ADMIN
│
├── PLSQL
│
├── SCRIPTS
│
├── DOCUMENTACAO
│
└── EXEMPLOS
```

---

# Boas Práticas

- Evite SELECT *
- Utilize índices adequadamente
- Atualize estatísticas
- Utilize bind variables
- Evite funções em colunas indexadas
- Analise o Explain Plan
- Documente consultas complexas
- Utilize aliases descritivos
- Prefira EXISTS em vez de IN quando apropriado
- Evite cursores desnecessários

---

# Roadmap

- SQL Básico
- SQL Intermediário
- SQL Avançado
- PL/SQL
- Administração Oracle
- Performance Tuning
- Data Warehouse
- Oracle RAC
- Oracle Exadata

---

# Referências

- Oracle Database Documentation
- Oracle SQL Language Reference
- Oracle PL/SQL Language Reference
- Oracle Performance Tuning Guide
- Oracle Data Warehousing Guide
- Oracle Database Concepts

---

# Licença

Este repositório destina-se ao estudo, documentação e compartilhamento de consultas Oracle.
