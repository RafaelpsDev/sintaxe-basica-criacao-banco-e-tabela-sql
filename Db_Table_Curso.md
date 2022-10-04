### Sintaxe Simples de criação de um banco e uma tabela em SQL.



**CREATE DATABASE DB_CURSO**
**GO**

**USE DB_CURSO**
**CREATE TABLE TB_CURSO**
**( ID_CURSO	INT		IDENTITY	NOT NULL PRIMARY KEY,**
  **NOME_CURSO	VARCHAR(50),**
  **DISCIPLINA	VARCHAR(50),**
**)**
