# Retail Store POS Data Analysis
## Objective
The objective of this repository is to analyze point of sale (POS) data from a retail store to better understand customer behavior, sales trends, and product performance.
## Overview
This repository contains SQL queries designed to answer key business questions using three tables: Customer, Transactions, and Product_Category. The focus is on deriving actionable insights from transactional and demographic data while maintaining data integrity and adhering to best practices in database management.
## Datasets
1.	<a href="https://github.com/SourabhaSekharRout/Retail-Store-POS-Data-Analysis/blob/main/Customer.csv">Customer</a>
   - Contains customer demographics.
3.	<a href="https://github.com/SourabhaSekharRout/Retail-Store-POS-Data-Analysis/blob/main/Transactions.csv">Transactions</a>
   - Contains transaction details.
5.	<a href="https://github.com/SourabhaSekharRout/Retail-Store-POS-Data-Analysis/blob/main/prod_cat_info.csv">Product Category</a>
   - Contains product category and sub-category details.
## Database Schema
![Screenshot 2024-12-12 165923](https://github.com/user-attachments/assets/c7db2ef0-3585-4384-ae28-9dd21b9993e3)
## Process
To set up and analyze the data, the following steps are performed:
- Use CREATE DATABASE to create the database.
- Define tables using CREATE TABLE statements with appropriate data types for each column.
- Establish primary and foreign keys to maintain data integrity between Customer, Transactions, and Product_Category tables.
- Use BULK INSERT statements to populate tables, adhering to the limit of 1000 records per statement in MS SQL Server.
## Business Queries
The repository provides SQL queries to answer the following questions:
- Data Preparation and Understanding
1.	Total number of rows in each of the three tables.
2.	Total number of transactions that have a return.
3.	Convert date variables into valid date formats.
4.	Determine the time range of transaction data in days, months, and years.
5.	Identify the product category for the sub-category "DIY."
- Data Analysis
1.	Most frequently used channel for transactions.
2.	Count of male and female customers.
3.	City with the maximum number of customers and their count.
4.	Number of sub-categories under the "Books" category.
5.	Maximum quantity of products ever ordered.
6.	Total revenue generated in "Electronics" and "Books" categories.
7.	Count of customers with more than 10 transactions (excluding returns).
8.	Combined revenue from "Electronics" and "Clothing" categories in "Flagship stores."
9.	Total revenue from male customers in the "Electronics" category, broken down by sub-category.
10.	Percentage of sales and returns by product sub-category, displaying only the top 5 sub-categories in terms of sales.
11.	Net total revenue from customers aged 25-35 years in the last 30 days of transactions from the maximum transaction date.
12.	Product category with the maximum value of returns in the last 3 months of transactions.
13.	Store type selling the maximum products by value of sales amount and by quantity sold.
14.	Categories with average revenue above the overall average.
15.	Average and total revenue by each sub-category for the top 5 categories in terms of quantity sold.
## Analysis
- <a href="https://github.com/SourabhaSekharRout/Retail-Store-POS-Data-Analysis/blob/main/Retail%20Store%20POS%20Data%20Analysis.sql">Analysis of Business Queries</a>
## Features
- Analyze customer behavior and transaction trends.
- Gain insights into sales performance across categories and sub-categories.
- Optimize SQL queries for performance and clarity.
- Ensure data integrity with proper database schema design.
