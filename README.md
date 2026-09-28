# SQL--DISTINCT
MySQL Assignment 2 covering SQL querying, filtering, sorting, aggregation, grouping, and joins using employee data.
# MySQL Assignment 2 – Querying Data



This repository contains my **MySQL Assignment 2**, focused on querying and analyzing employee data using SQL.

The assignment continues from the database and table structure created in Assignment 1 and covers SQL querying concepts such as filtering, sorting, aggregation, grouping, and joins.

## 🗄️ Database Structure

The project uses an employee database with the following tables:

- `employees`
- `departments`
- `location`

### Employees Table

Contains employee information such as:

- Employee ID
- Employee Name
- Gender
- Age
- Hire Date
- Designation
- Department ID
- Location ID
- Salary

### Departments Table

Contains:

- Department ID
- Department Name

### Location Table

Contains:

- Location ID
- Location

## 🔍 SQL Concepts Covered

### Basic Queries
- `SELECT`
- `DISTINCT`
- Column aliases using `AS`
- `WHERE`
- Comparison operators
- `AND`

### Sorting and Limiting
- `ORDER BY`
- `ASC`
- `DESC`
- `LIMIT`

### Aggregate Functions
- `SUM()`
- `MIN()`
- `AVG()`
- `MAX()`
- `COUNT()`

### Grouping and Filtering
- `GROUP BY`
- `HAVING`
- `LIKE`

### Joins
- `INNER JOIN`
- `LEFT JOIN`
- `RIGHT JOIN`

## 📋 Assignment Tasks

The assignment includes queries to:

1. Retrieve distinct salaries.
2. Create aliases for age and salary.
3. Retrieve employees based on salary and hire date conditions.
4. Find and update missing employee designation.
5. Sort employees by department ID and salary.
6. Display the first five employees hired in 2018.
7. Calculate the total salary in the Finance department.
8. Find the minimum employee age.
9. Find the maximum salary for each location.
10. Calculate average salary for designations containing "Analyst".
11. Find departments with fewer than three employees.
12. Find locations where female employees have an average age below 30.
13. Use an `INNER JOIN` to display employee and department information.
14. Use a `LEFT JOIN` to count employees in every department, including departments with no employees.
15. Use a `RIGHT JOIN` to display all locations and their assigned employees.

## 🛠️ Tools Used

- MySQL
- MySQL Workbench
- SQL

## 📁 Project Files

The repository contains the SQL file with the database setup, table creation, data insertion, and Assignment 2 queries.

## 🎯 Learning Objective

The purpose of this assignment is to practice SQL querying and understand how relational tables can be filtered, sorted, grouped, aggregated, and combined using different types of joins.

