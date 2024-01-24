# Demo DAO JDBC
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/RafaelCecyn/demo-dao-jdbc/blob/main/LICENSE)  

# Sobre o projeto
Demo DAO JDBC é um exemplo de como acessar o banco de dados MySQL usando Java e o padrão de projeto DAO (Data Access Object). O projeto utiliza duas tabelas, `department` e `seller`.

## **Tabelas**

As tabelas `department` e `seller` são entidades do banco de dados. Para cada tabela, foi criada uma interface correspondente para implementar os métodos básicos de CRUD (Create, Read, Update, Delete).

## **Métodos**

Os métodos implementados são:

- **insert**: insere uma nova linha na tabela.
- **delete**: remove uma linha da tabela com base em algum critério.
- **update**: atualiza uma linha existente na tabela.
- **find**: busca uma ou mais linhas da tabela com base em algum critério.

## **Uso**

Para usar este projeto, primeiramente você precisará executar o arquivo database.sql para criar as tabelas `department` e `seller`.
Após, necessitará configurar a sua conexão com o banco de dados que se encontra no arquivo `db.properties` e alterar o seu user e password.

# Tecnologias utilizadas
## Back end
- Java

# Como executar o projeto

## Back end
Pré-requisitos: Java 17

```bash
# clonar repositório
git clone https://github.com/RafaelCecyn/demo-dao-jdbc
```

# Autor

Rafael Cecyn Mendes

https://www.linkedin.com/in/rafaelcecynmendes/
