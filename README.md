# hive_cmd
**********************************************************
## Hive's Command ->
*********************************************************

## 1. create database
CREATE DATABASE my_database;

## 2. use database
USE my_database;

## 3. create table
CREATE TABLE my_table (
    id INT,
    name STRING
);

## 4. insert 1 value
insert into my_table values(1,'mudit');

## 5. insert many values
insert into my_table values(2,'maaz'),(3,'shivam'),(4,'aman'),(5,'ishu');


## 6. view
CREATE VIEW my_view AS
SELECT * FROM my_table WHERE id > 3;


## 7. drop view
DROP VIEW my_view;


## 8. drop table
DROP TABLE IF EXISTS my_table;


## 9. drop database
DROP DATABASE IF EXISTS my_database;


## 10. outside 
quit / exit


## 11. Open in browser ->
http://localhost:9870/explorer.html#/user/hive/warehouse 



