# SQL
**SQL stands for Structured Query Language**

# SQL & Relational database
Relational databases store data in tables which can grow large and have a multitude of columns and records. 
Relational database management systems (RDBMSs) use SQL (and variants of SQL) to manage the data in these large tables.

 SQL: is a standardized programming language that is used to manage relational databases and perform various operations on the data in them.
```
SELECT * FROM TableName; select all things inside table
```
```
SELECT column1, column2, ...
FROM table_name;
select certain columns
```
```
SELECT DISTINCT column1, column2, ...
FROM table_name;
select data without duplicated
```
```
SELECT column1, column2, ...
FROM table_name
WHERE condition;
select data according to condition
```
```
SELECT column1, column2, ...
FROM table_name
WHERE condition1 AND condition2;

SELECT column1, column2, ...
FROM table_name
WHERE condition1 OR condition2 ;

select data using multi condition
```
```
SELECT column1, column2
FROM table_name
ORDER BY column1, column2  ASC|DESC;

ASC: from high to low
DESC: from low to high
```
```
INSERT INTO table_name (column1, column2)
VALUES (value1, value2);

insert new data
```
```
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;

update data
```
```
DELETE FROM table_name WHERE condition;
delete row 
```
```
SELECT column1, column2, ...
FROM table_name
WHERE columnN LIKE "%";

select data according to certain pattern
```
![image](./Screenshot%20(124).png)
