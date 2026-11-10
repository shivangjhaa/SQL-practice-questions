# SQL Interview Questions

A collection of SQL interview questions covering basic queries, joins, subqueries, aggregate functions, window functions, CTEs, and advanced SQL concepts.

## 1. Salary & Employee Queries

1. Write a SQL query to find the second-highest salary from an employee table. *
2. Write a SQL query to find the second-lowest salary without using LIMIT or OFFSET.
3. Write a SQL query to find the Nth highest salary from an employee table (e.g., 5th highest).
4. Write a SQL query to find employees who earn more than the average salary of their department. *
5. Write a SQL query to find employees who have the same manager.
6. Write a SQL query to find employees who are also managers.
7. Write a SQL query to find employees older than the average age of employees in their department.
8. Write a SQL query to find employees whose salaries fall within the top 10% of their department.
9. Write a SQL query to find the median salary of employees.
10. Write a SQL query to count how many employees share the same salary.
11. Write a SQL query to find employees whose names contain the letter "a" exactly twice.

## 2. Date & Time Queries

1. Write a SQL query to find the first and last record for each employee based on the hire_date column.
2. Write a SQL query to find the total number of employees hired per month and year.
3. Write a SQL query to find employees who joined in the same month and year.
4. Write a SQL query to find the employee(s) with the longest tenure at the company.
5. Write a SQL query to retrieve records from the last 7 days.
6. Write a SQL query to identify orders placed during business hours (9 AM to 6 PM).
7. Write a SQL query to find users who logged in consecutively for 3 days or more.
8. Write a SQL query to count users active on both weekdays and weekends.

## 3. Joins & Subqueries

1. Write a SQL query to list all products that have never been ordered or sold. *
2. Write a SQL query to find all pairs of products ordered together at least once.
3. Write a SQL query to retrieve customers who purchased products from at least three different categories.
4. Write a SQL query to find the most frequently occurring value in a column.

## 4. Aggregation & GROUP BY

1. Write a SQL query to calculate the total salary of each department and display departments whose total salary exceeds 50,000.
2. Write a SQL query to calculate the average order value per customer for each month.
3. Write a SQL query to find the total revenue for each region in a given quarter.
4. Write a SQL query to calculate the ratio of sales between two product categories.
5. Write a SQL query to retrieve only duplicate records from a table.

## 5. Window Functions & Ranking

1. Write a SQL query to find the running total of orders for each customer, sorted by order date.
2. Write a SQL query to calculate the running total of sales by date.
3. Write a SQL query to retrieve the top 3 records for each group in a table.
4. Write a SQL query to rank products by sales in descending order for each region.
5. Write a SQL query to calculate year-on-year revenue growth.
6. Write a SQL query to calculate the percentage change in sales month-over-month.

## 6. Customer & Transaction Queries

1. Write a SQL query to find the most recent transaction for each customer.
2. Write a SQL query to find the first purchase date of each customer.
3. Write a SQL query to retrieve customers who made their first purchase in the last 6 months.
4. Write a SQL query to identify customers who made at least one purchase every month for the past year.

## 7. Advanced SQL & CTEs

1. Write a SQL query to pivot a table by converting rows into columns.
2. Write a SQL recursive query to generate a hierarchical structure.
3. Write a SQL query to find gaps in sequential numbering within a table.
4. Write a SQL query to split a comma-separated string into individual rows.

## 8. Data Cleaning & DELETE Operations

1. Write a SQL query to delete all records where a specified column contains NULL.
2. Write a SQL query to delete duplicate rows while keeping one occurrence.