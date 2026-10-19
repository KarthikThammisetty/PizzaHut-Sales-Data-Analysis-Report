🍕 PizzaHut SQL Sales Analysis

📌 Project Overview

This project focuses on analyzing PizzaHut’s pizza sales data using MySQL to extract meaningful business insights and understand sales performance, customer ordering patterns, and product demand.

Using SQL queries, I explored order volumes, revenue generation, pizza popularity, category-wise sales, and ordering trends throughout the day. The project demonstrates how SQL can transform raw transactional data into meaningful insights that can support data-driven business decisions.

🎯 Project Objectives

* Calculate the total number of orders placed.
* Analyze total revenue generated from pizza sales.
* Identify the highest-priced pizza.
* Determine the most popular pizza sizes.
* Identify the top 5 most-ordered pizza types by quantity.
* Analyze order distribution by hour of the day.
* Examine the distribution of pizza types across categories.
* Calculate the average number of pizzas ordered per day.
* Identify the top 3 pizza types by revenue.
* Calculate the percentage contribution of each pizza category to total revenue.
* Rank the top 3 revenue-generating pizza types within each category.

🛠️ Tools & Technologies

* Database: MySQL
* Query Language: SQL
* Analysis Techniques: Data Aggregation, Joins, Subqueries, Sorting, Grouping, and Window Functions

🗂️ Database Tables

The analysis uses four relational tables:

Table	Description
orders	Contains order-level information, including order date and time.
orders_details	Contains order-line information, including pizza IDs and quantities.
pizzas	Contains pizza variant details, including size and price.
pizza_types	Contains pizza names and their categories.

These tables are joined to analyze sales performance at the order, product, and category levels.

🔍 Key Business Questions & SQL Analysis

1. Sales Performance

* How many orders were placed?
* What is the total estimated revenue generated from pizza sales?
* What is the average number of pizzas sold per day?

2. Product Analysis

* Which pizza has the highest price?
* Which pizza sizes and types are most popular?
* Which are the top 5 pizza types by quantity sold?

3. Order Trends

* During which hours are the most orders placed?
* How does order volume vary throughout the day?

4. Revenue Analysis

* Which pizza types generate the highest revenue?
* What percentage of total revenue comes from each pizza category?
* Which pizza types generate the highest revenue within each category?

💡 SQL Concepts Demonstrated

This project demonstrates practical SQL skills, including:

* Aggregate Functions: COUNT(), SUM(), AVG(), ROUND()
* Joins: INNER JOIN across multiple related tables
* Grouping & Sorting: GROUP BY, ORDER BY
* Filtering Results: LIMIT, WHERE
* Subqueries: Calculating daily averages and total revenue
* Date & Time Functions: HOUR()
* Window Functions: RANK() OVER (PARTITION BY ... ORDER BY ...)
* Business Metrics: Revenue calculation, product ranking, and percentage contribution analysis

📊 Business Value

The analysis can help answer important business questions related to:

* Sales Performance: Understand order volume and estimated sales revenue.
* Product Strategy: Identify high-demand and high-revenue pizza types.
* Menu Planning: Evaluate demand across pizza sizes and categories.
* Operational Efficiency: Understand peak ordering hours to support staffing and preparation planning.
* Revenue Contribution: Identify categories that contribute most to estimated sales.

These insights can support better decisions around product promotion, inventory planning, and operational efficiency.

📁 Project Structure

PizzaHut-SQL-Analysis/
│
├── README.md
├── sql/
│   └── pizza_sales_analysis.sql
├── reports/
│   └── PizzaHut_SQL_Sales_Analysis_Report.pdf
└── data/
    └── Dataset files

Adjust the folder and file names to match the structure of your actual GitHub repository.

📈 Key Learnings

Through this project, I strengthened my ability to:

* Write SQL queries to analyze relational datasets.
* Combine multiple tables using joins.
* Calculate business metrics using aggregate functions.
* Analyze product demand and estimated revenue.
* Apply subqueries and window functions to solve analytical problems.
* Translate business questions into SQL queries.
* Interpret data from a business and decision-making perspective.

🚀 Conclusion

The PizzaHut SQL Sales Analysis project demonstrates how SQL can be used to explore transactional sales data and answer practical business questions.

By combining data aggregation, relational joins, revenue calculations, and ranking techniques, this project provides a foundation for understanding product performance, ordering patterns, and sales contribution.

This project is part of my journey toward developing practical Data Analytics and Business Intelligence skills.

⸻

Author: Karthik Thammisetty
Project: PizzaHut SQL Sales Analysis
Technology: MySQL
Domain: Sales Analytics | Data Analytics | Business Intelligence
