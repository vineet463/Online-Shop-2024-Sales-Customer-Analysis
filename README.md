# Online-Shop-2024-Sales-Customer-Analysis

### About the Project

Online retail businesses generate thousands of transactions every day, but raw data alone doesn't help in making business decisions.

In this project, I analyzed the Online Shop 2024 dataset using MySQL to understand how the business is performing. The analysis focuses on customer behavior, sales performance, supplier contribution, product performance, and shipping efficiency.

The goal of this project was not only to practice SQL but also to answer real business questions that an e-commerce company might ask before making business decisions.

### Business Background

The company sells products through an e-commerce platform and receives orders from customers across different regions. Every purchase generates information about customers, products, suppliers, payments, shipments, and customer reviews.

Although the company collects this data every day, management cannot make informed decisions by looking at raw tables alone. They need meaningful insights to understand business performance and identify opportunities for improvement.

### Business Problem

The management team wants to better understand the overall performance of the business.
These are some of the business questions that the management wants answers to

How much revenue has the company generated?
Which products contribute the most sales?
Who are the most valuable customers?
Which suppliers perform the best?
How efficient is the delivery process?
Which customers have become inactive?

Instead of manually reviewing thousands of records, SQL can be used to answer these questions quickly and accurately.

#### Project Objectives
- Analyze the overall sales performance.
- Understand customer purchasing behaviour.
- Identify the highest revenue-generating products.
- Evaluate supplier performance.
- Measure delivery efficiency.
- Demonstrate SQL skills using a relational database.

### Dataset 

Online Shop 2024 Dataset (Kaggle)
[Online Shop 2024 Dataset.zip](https://github.com/user-attachments/files/30084717/Online.Shop.2024.Dataset.zip)

### Database Design

The dataset was imported into MySQL Workbench as a relational database.

After importing the data:
Primary Keys were added.
Foreign Keys were established.
Relationships between tables were verified.

The final database structure is shown below.
<img width="1168" height="862" alt="Screenshot 2026-07-16 161635" src="https://github.com/user-attachments/assets/7d9c85e8-d347-4a86-a3ef-64907b046551" />

### SQL Concepts Used
Aggregate Functions
GROUP BY
HAVING
INNER JOIN
Multiple Table JOINs
Subqueries
Common Table Expressions (CTEs)
Window Functions
Date Functions

### Business Questions

-1	Total number of customers
-2	Total number of orders
-3	Total revenue
-4	Top 10 products by sales
...	...
 Detailed SQL analysis and query results can be found in:

[Business Analysis Report](documentation/business_analysis.md)
