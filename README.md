# 🍕 Pizza Sales SQL Analysis Project

**Prepared by:** Anjali Negi

**Project Type:** SQL Data Analytics

**Database:** MySQL

## 📌 Project Overview

The **Pizza Sales SQL Analysis Project** focuses on analyzing pizza sales data using SQL. The purpose of this project is to transform raw order data into meaningful business insights related to sales performance, customer ordering patterns, popular pizzas, pizza categories, sizes, and revenue.

The project includes SQL queries ranging from basic data retrieval to intermediate and advanced business analysis.

## 🎯 Project Objectives

* Calculate the total number of orders.
* Find the total revenue generated from pizza sales.
* Identify the highest-priced pizza.
* Find the most commonly ordered pizza size.
* Identify the most popular pizza types.
* Analyze sales by pizza category.
* Understand order patterns by date and hour.
* Calculate revenue contribution by pizza type.
* Analyze cumulative revenue over time.
* Identify the top-performing pizzas within each category.

## 🛠️ Tools and Technologies

* **MySQL:** Database management and SQL query execution
* **SQL:** Data extraction, transformation, aggregation, and analysis
* **PowerPoint:** Project presentation and visualization
* **CSV Files:** Source datasets

## 📂 Project Files

| File                           | Description                                                                 |
| ------------------------------ | --------------------------------------------------------------------------- |
| `Pizza_Sales_SQL_Project.pptx` | Project presentation containing the project overview and analysis questions |
| `Questions.txt`                | List of SQL business questions                                              |
| `README.md`                    | Project documentation                                                       |
| `order_details.csv`            | Dataset containing details of individual pizza items in each order          |
| `orders.csv`                   | Dataset containing order-level information                                  |
| `pizza_types.csv`              | Dataset containing pizza names, categories, and ingredients                 |
| `pizzas.csv`                   | Dataset containing pizza sizes and prices                                   |

## 🗃️ Dataset Description

### 1. orders.csv

Contains information about customer orders, such as:

* Order ID
* Order date
* Order time

### 2. order_details.csv

Contains information about individual pizza items included in orders, such as:

* Order ID
* Pizza ID
* Pizza quantity

### 3. pizzas.csv

Contains pizza-level information, such as:

* Pizza ID
* Pizza type ID
* Pizza size
* Pizza price

### 4. pizza_types.csv

Contains information about pizza types, such as:

* Pizza type ID
* Pizza name
* Pizza category
* Ingredients

> The exact column names should be confirmed from the CSV files before writing the final SQL queries.

## 🧠 SQL Concepts Used

This project uses the following SQL concepts:

* CREATE DATABASE
* CREATE TABLE
* SELECT
* WHERE
* JOIN
* GROUP BY
* ORDER BY
* COUNT()
* SUM()
* AVG()
* MAX()
* Date and time functions
* Subqueries
* Window functions
* Percentage calculations
* Cumulative totals

## 📊 Analysis Questions

### Basic Analysis

1. Create the database and tables.
2. Retrieve the total number of orders placed.
3. Calculate the total revenue generated from pizza sales.
4. Identify the highest-priced pizza.
5. Identify the most common pizza size ordered.
6. List the top 5 most ordered pizza types along with their quantities.

### Intermediate Analysis

7. Find the total quantity of each pizza category ordered.
8. Determine the distribution of orders by hour of the day.
9. Find the category-wise distribution of pizzas.
10. Group orders by date and calculate the average number of pizzas ordered per day.
11. Determine the top 3 most ordered pizza types based on revenue.

### Advanced Analysis

12. Calculate the percentage contribution of each pizza type to total revenue.
13. Analyze the cumulative revenue generated over time.
14. Determine the top 3 most ordered pizza types based on revenue for each pizza category.

## 🚀 How to Run the Project

1. Install and open MySQL Workbench.
2. Create a database for the pizza sales project.
3. Create the required tables using the CSV column structure.
4. Import the CSV datasets into MySQL.
5. Verify the relationships between the tables.
6. Execute the SQL queries from the basic, intermediate, and advanced sections.
7. Save the query outputs or screenshots.
8. Add the SQL code and results to the PowerPoint presentation.

## 🔗 Table Relationships

The datasets can be connected using common identifiers:

* `orders.order_id` → `order_details.order_id`
* `order_details.pizza_id` → `pizzas.pizza_id`
* `pizzas.pizza_type_id` → `pizza_types.pizza_type_id`

> Confirm the exact column names and data types in the CSV files before creating the database tables.

## 📈 Expected Outcomes

The project is expected to provide insights into:

* Total orders and total revenue
* Most popular pizza sizes
* Best-selling pizza types
* Category-wise pizza demand
* Peak ordering hours
* Average daily pizza sales
* Revenue contribution by pizza type
* Cumulative revenue trends
* Top-performing pizzas within each category

## 💼 Business Value

The results of this analysis can help a pizza business understand:

* Which products are most popular
* Which categories generate more sales
* When customer demand is highest
* Which products contribute most to revenue
* How sales trends change over time
* How data can support inventory and business planning

## 📌 Project Status

* [x] Project presentation created
* [x] SQL business questions prepared
* [x] Dataset files added
* [x] README documentation created
* [ ] SQL database and tables created
* [ ] SQL queries completed
* [ ] Query results added to the presentation
* [ ] Final business insights documented

## ✅ Conclusion

The **Pizza Sales SQL Analysis Project** demonstrates practical SQL and data analytics skills. It uses multiple related datasets to analyze orders, pizza details, categories, quantities, prices, and revenue.

The project covers database creation, table relationships, joins, aggregation, time-based analysis, and advanced SQL techniques. The final query results can be used to present clear, data-driven business insights.

## 👩‍💻 Author

**Anjali Negi**

**Project:** Pizza Sales SQL Analysis
