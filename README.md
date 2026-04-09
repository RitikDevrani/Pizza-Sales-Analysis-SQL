# Pizza Sales Analysis (SQL Project)
# Project Overview
This project focuses on analyzing pizza sales data using SQL to extract meaningful business insights.

The analysis includes order trends, revenue calculation, product performance, and customer behavior, helping in understanding how a pizza business operates and performs.

## Objectives
The main goals of this project are:

• Calculate total number of orders

• Analyze total revenue generated

• Identify top-performing pizzas

• Understand customer ordering patterns

• Analyze sales by category, size, and time

• Generate business insights using SQL queries

## Database Structure
The project uses a MySQL database named:

• pizzahut

Tables Used:

### 1. orders
• order_id (Primary Key)

• order_date

• order_time


### 2. orders_details
• order_details_id (Primary Key)

• order_id

• pizza_id

• quantity


### 3. pizzas
• pizza_id

• pizza_type_id

• size

• price


### 4. pizza_types
• pizza_type_id

• name

• category


## Key SQL Analysis Performed
### Basic Analysis
• Total number of orders

• Total revenue generated

• Highest priced pizza

• Most common pizza size


### Intermediate Analysis
• Top 5 most ordered pizzas

• Quantity sold by category

• Orders distribution by hour

• Category-wise pizza count


### Advanced Analysis
• Average pizzas ordered per day

• Top 3 pizzas based on revenue

• Revenue contribution by category (%)

• Cumulative revenue over time (Window Function)

• Top 3 pizzas per category using RANK()


## Sample Insights
• Certain pizza categories contribute more to revenue

• Peak order hours can be identified using time analysis

• A few pizzas dominate overall sales

• Revenue trends can be tracked over time using cumulative analysis


## Tools & Technologies Used
• MySQL

• SQL (Joins, Aggregations, Window Functions, Subqueries)

• CSV Data Files


## Project Structure
Pizza-Sales-Analysis

• Pizza Sales Analysis.sql

• orders.csv

• order_details.csv

• pizzas.csv

• pizza_types.csv

• README.md


## How to Run This Project
### 1. Create Database
• Run the SQL script:

CREATE DATABASE pizzahut;

USE pizzahut;

### 2. Create Tables
• Execute table creation queries from the SQL file.

### 3. Import Data
• Import CSV files into respective tables using:

LOAD DATA INFILE 'file_path'

INTO TABLE table_name

FIELDS TERMINATED BY ','

ENCLOSED BY '"'

LINES TERMINATED BY '\n'

IGNORE 1 ROWS;


### 4. Run Queries
• Execute the analysis queries to generate insights.

## Learning Outcomes
• Strong understanding of SQL queries

• Hands-on experience with Joins and Aggregations

• Use of Window Functions (RANK, SUM OVER)

• Real-world data analysis using SQL

• Writing optimized and structured queries


## Future Improvements
• Create Power BI dashboard for visualization

• Add advanced KPIs like profit and growth rate

• Automate reporting using stored procedures

• Optimize queries for performance


## Author

• Ritik Devrani

• Diploma in Computer Science

• BCA (IGNOU)
