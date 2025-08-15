# Exploratory-data-Analysis-EDA-
Exploratory Data Analysis (EDA) using SQL on a retail sales dataset. Queries demonstrate aggregation, joins, window functions, and reporting in PostgreSQL.

## Project Overview
This project demonstrates a comprehensive Exploratory Data Analysis (EDA) using SQL on a sample retail sales dataset.  
The primary goal is to extract meaningful insights from sales, products, and customer data using advanced SQL queries.  
It showcases key SQL concepts such as aggregation, window functions, joins, and reporting queries in PostgreSQL.

---
## Tools Used
- **DBeaver** → SQL client for writing and executing queries.
- **PostgreSQL** → Database system for running queries.
---
## Key Objectives
- Analyze business performance and key metrics.
- Identify trends in customer behavior, sales, and products.
- Evaluate top-performing and underperforming products.
- Summarize revenue and orders across categories, customers, and countries.

---
## Features / Analysis Conducted
1. **Database Exploration**
   - List all tables and columns.
   - Inspect schema structure and relationships.
2. **Customer Insights**
   - Identify youngest and oldest customers.
   - Count total customers and customers who placed orders.
   - Customer distribution by country and gender.
3. **Sales Analysis**
   - Total sales, average selling price, total quantity sold, and total orders.
   - Sales trends across time (first and last order, sales duration in years).
4. **Product Analysis**
   - Total products, product distribution by category, average product cost.
   - Identify top 5 highest revenue products and 5 lowest revenue products.
5. **Revenue Analysis**
   - Total revenue by category and by customer.
   - Generate a consolidated report of key business metrics using UNION ALL.
6. **Advanced SQL Techniques**
   - Use of `DENSE_RANK` for top product ranking.
   - Window functions for analytical queries.
   - Joins (`LEFT JOIN`, `INNER JOIN`) for data consolidation.
   - Aggregation (`SUM`, `COUNT`, `AVG`, `MIN`, `MAX`) and grouping (`GROUP BY`).

---
