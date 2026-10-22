## 1. What is a LEFT JOIN in SQL?
A LEFT JOIN returns all records from the left table and the matching records from the right table; if there is no match, it returns NULL for the right table's columns.

## 2. What is a FULL JOIN in SQL?
A FULL JOIN returns all records from both tables, including matching and non-matching records, with NULL values where no match exists.

## 3. What are the rules for using the GROUP BY clause?
GROUP BY groups rows with the same values, and every selected column must either be included in GROUP BY or used inside an aggregate function, except where the database permits other valid expressions.

## 4. What is the difference between single-row functions and multi-row functions in SQL?
Single-row functions operate on one row at a time, such as UPPER() and LENGTH(), while multi-row (aggregate) functions operate on multiple rows and return a single result, such as SUM(), AVG(), and COUNT().

## 5. What is durability in DBMS?
Durability is an ACID property that ensures committed transaction changes remain saved, even after a system crash or power failure.

## 6. What is isolation in DBMS?
Isolation is an ACID property that ensures concurrent transactions do not interfere with each other in ways that produce incorrect results.

## 7. What is the difference between a primary key and a unique key?
A primary key uniquely identifies each row and cannot contain NULL values, while a unique key prevents duplicate values and may allow NULL values depending on the database system.

## 8. What is the difference between the WHERE and HAVING clauses?
WHERE filters individual rows before grouping, while HAVING filters groups after GROUP BY, often using aggregate functions.

## 9. What is DDL (Data Definition Language)?
DDL is a category of SQL commands used to define or modify database structures, such as CREATE, ALTER, DROP, and TRUNCATE.

## 10. What is partition tolerance in the CAP theorem?
Partition tolerance means a distributed system continues operating despite communication failures between nodes, even when some nodes cannot communicate with others.