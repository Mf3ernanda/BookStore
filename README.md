# Bookstore API

## Descrição

A API **Bookstore** é uma aplicação desenvolvida em Spring Boot para gerenciar livros, autores, editores e resenhas. Esta API permite realizar operações de criação, atualização e recuperação de informações sobre livros e seus relacionados. O banco de dados é composto pelas tabelas `tb_publisher`, `tb_author`, `tb_review`, `tb_book`, e `tb_book_author`.

## Funcionalidades

A API oferece os seguintes endpoints principais:

* **GET** `/books` - Recupera todos os livros.
* **GET** `/books/{id}` - Recupera um livro específico por ID.
* **PUT** `/books/{id}` - Atualiza um livro existente.

## Estrutura do Banco de Dados

As tabelas do banco de dados são:

* **tb_publisher**: Contém informações sobre os editores.
* **tb_author**: Contém informações sobre os autores.
* **tb_review**: Contém as resenhas dos livros.
* **tb_book**: Contém informações sobre os livros.
* **tb_book_author**: Relaciona livros e autores.

## A API estará disponível 
* http://localhost:8080.

## Dependências

* Spring Boot Starter Web
* Spring Boot Starter Data JPA
* PostgreSQL Driver
