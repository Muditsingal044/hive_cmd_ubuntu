# hive_cmd_ubuntu
**********************************************************
## Hive's Command On Ubuntu 
*********************************************************

## 1. create database
CREATE DATABASE my_database;

## 2. use database
USE my_database;

## 3. create table
CREATE TABLE my_table1 (
    id INT,
    name STRING
);

## 4. insert 1 value
insert into my_tables1 value(1,'mudit');

## 5. insert many values
insert into my_tables1 value(2,'maaz'),(3,'shivam'),(4,'aman'),(5,'ishu');

## 6. alter
ALTER TABLE my_table ADD COLUMN age INT;

## 7. view
CREATE VIEW my_view AS
SELECT id, name FROM my_table WHERE age > 18;


## 8. function
CREATE FUNCTION my_function AS 'org.example.MyFunctionClass';

## 9. index create
CREATE INDEX my_index ON TABLE my_table (name) AS 'COMPACT';


## 10. drop index
DROP INDEX my_index ON my_table;

## 11. drop function
DROP FUNCTION my_function;


## 12. drop view
DROP VIEW my_view;


## 13. drop table
DROP TABLE IF EXISTS my_table;


## 14. drop database
DROP DATABASE IF EXISTS my_database;


## 15. outside 
quit / exit


## 16. Open in browser - 
http://localhost:9083



