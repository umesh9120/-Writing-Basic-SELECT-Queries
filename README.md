# -Writing-Basic-SELECT-Queries

**Objective:**
Practice SQL data retrieval using SELECT with conditions, sorting, and filtering.

**Tool Used:**
MySQL Workbench / DB Browser for SQLite

**Database Overview**

Database: employees

Table: employees_data

Fields:

id (INT, Primary Key)

name (VARCHAR)

age (INT)

salary (INT)

**Queries Performed**

1️⃣ Basic Retrieval

SELECT * FROM employees_data;

SELECT id FROM employees_data;

SELECT name FROM employees_data;

2️⃣ Filtering Data

SELECT * FROM employees_data WHERE salary < 40000;

SELECT * FROM employees_data WHERE salary < 40000 AND age < 25;

SELECT * FROM employees_data WHERE salary > 45000 OR age < 25;

3️⃣ Range & Set Matching

SELECT * FROM employees_data WHERE salary BETWEEN 35000 AND 40000;

SELECT * FROM employees_data WHERE age IN (21,22,23,24);

4️⃣ Pattern Matching

SELECT * FROM employees_data WHERE name LIKE 'S%';

5️⃣ Sorting

SELECT * FROM employees_data ORDER BY salary ASC;

SELECT * FROM employees_data ORDER BY salary DESC;

**Key Learnings**

Retrieve all or specific columns using SELECT.

Filter rows with WHERE, AND, OR, LIKE, BETWEEN, and IN.

Sort results with ORDER BY ASC/DESC.
