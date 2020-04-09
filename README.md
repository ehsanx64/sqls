# sqls

## Introduction
SQL sample source code written in various dialects (T-SQL, MySQL\MariaDB, PostgreSQL)

## Overview of Folders
### **mariadb**: This folder contains source code written specificly for MariaDB.
### **mysql**: This folder contains source code written for MySQL and/or MariaDB.
### **psql**: This folder contains source code written for PostgreSQL.
### **tsql**: This folder contains source code written for Microsoft SQL Server using T-SQL.

## MySQL
### Dynamic Query
A simple and quick method for re-using MySQL queries is scripting. This task can be easily achieved by saving the query (sql) code to a text file; ideally with .sql file-extension; then execute it. This sql script file, can be executed both interactively (for example from mysql shell) or as a normal shell command or in a shell script.

In DynamicQuery.sql, four variables are used to generate a SQL query. A statement will be created from the query string and after executing the statement, results will be returned. At end the prepared statement will be deallocated.