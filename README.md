# Banco de Dados - SQL ⋆｡°✩
## Passo a passo: Criação de um banco de dados
Tutorial de como criar um banco de dados SQL que organiza as informações de 'livros', 'editora', 'autores' e 'assuntos'.<br>
Este guia será dividido em etapas para demonstrar desde a criação de tabelas, chaves e até manipulação/consulta de dados.

## Resumo de uma estrutura SQL
* __CREATE__ para criar 'Banco de Dados' ou 'Tabelas'<br>
* __ALTER__ para adicionar ou modificar colunas<br>
* __DROP__ para remover 'Banco de Dados' ou 'Tabelas'<br>
* __INSERT__ para adicionar registros na tabela<br>
* __UPDATE__ para atualizar os registros<br>
* __DELETE__ para remover os registros<br>
* __SELECT__ para consultar e visualizar os registros<br>

## Passo 1: Criação do Banco de Dados e das Tabelas
#### 1.1 Criando o DB

```
CREATE DATABASE biblioteca;
USE biblioteca;
```

#### 1.2 Criando a tabela 'editora'

```
CREATE TABLE editora (
    id_editora INT PRIMARY KEY AUTO_INCREMENT,
    nome_editora VARCHAR(100) NOT NULL,
    pais VARCHAR (50)
);
```
#### 1.3 Criando a tabela 'autor'
```
CREATE TABLE autor (
    id_autor INT PRIMARY KEY AUTO_INCREMENT,
    nome_autor VARCHAR (100),
    data_nascimento DATE
);
```

#### 1.4 Criando a tabela 'assunto'
```
CREATE TABLE assunto (
    id_assunto INT PRIMARY KEY AUTO_INCREMENT,
    descricao VARCHAR (500) NOT NULL
);
```

#### 1.5 Criando a tabela 'livro'
```
CREATE TABLE livro (
    id_livro INT PRIMARY KEY AUTO_INCREMENT,
    
);
```