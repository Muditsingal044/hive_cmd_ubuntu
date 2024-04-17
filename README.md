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

## insert 1 value
insert into my_tables1 value(1,'mudit');

## insert many values
insert into my_tables1 value(2,'maaz'),(3,'shivam'),(4,'aman'),(5,'ishu');

## alter
ALTER TABLE my_table ADD COLUMN age INT;

## view
CREATE VIEW my_view AS
SELECT id, name FROM my_table WHERE age > 18;


## function
CREATE FUNCTION my_function AS 'org.example.MyFunctionClass';

## index create
CREATE INDEX my_index ON TABLE my_table (name) AS 'COMPACT';


## drop index
DROP INDEX my_index ON my_table;

## drop function
DROP FUNCTION my_function;


## drop view
DROP VIEW my_view;


## drop table
DROP TABLE IF EXISTS my_table;


## drop database
DROP DATABASE IF EXISTS my_database;


## outside 
quit / exit


## Open in browser - 
http://localhost:9083



