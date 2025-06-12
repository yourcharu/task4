# Task-4-SQL
This project focuses on analyzing e-commerce transaction data stored in a PostgreSQL database using advanced SQL. Key business insights such as revenue trends, top customer segments, category performance, and sales timelines were extracted through queries involving aggregation, subqueries, views, and indexing.
 SQL Project: E-Commerce Sales Analysis
 Project Overview:-
This project involves performing comprehensive analysis on an e-commerce transaction dataset using SQL in PostgreSQL. It covers multiple dimensions such as customer behavior, sales trends, category insights, and revenue metrics using optimized SQL queries and views.

Database Schema:-
Table: 

| Column Name       | Data Type  | Description                          |
|-------------------|------------|--------------------------------------|
| transactions_id   | INT        | Unique transaction ID                |
| sale_date         | DATE       | Date of the transaction              |
| sale_time         | TIME       | Time of the transaction              |
| customer_id       | INT        | Unique customer ID                   |
| gender            | TEXT       | Gender of the customer               |
| age               | INT        | Age of the customer                  |
| category          | VARCHAR    | Product category                     |
| quantity          | INT        | Number of items sold                 |
| price_per_unit    | FLOAT      | Price per unit                       |
| cogs              | FLOAT      | Cost of goods sold                   |
| total_sale        | FLOAT      | Total revenue from the transaction   |


Key Insights & Queries:-

- Total revenue and sales by category
- Top 5 high-spending customers
- Sales volume by hour and date
- Gender-based purchase patterns
- High-value customers (above average spending)

Features Implemented:-

-  SQL queries using `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`
-  Subqueries and aggregations (`SUM`, `AVG`)
-  Custom views for modular reporting
-  Indexes for performance optimization
-  Join with a mock `customers` table

