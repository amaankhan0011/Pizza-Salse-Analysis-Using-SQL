# 🍕 Pizza Sales Analysis - SQL Project

## 📌 Project Overview

This project analyzes pizza sales data using SQL to uncover key business insights. The dataset includes details on orders, pizza types, and sales transactions. By leveraging SQL queries, we extract meaningful insights to help optimize sales strategies and understand customer preferences.

## 📂 Dataset Overview

The project consists of the following tables:

### Orders Table

order_id, order_date, order_time

- Tracks individual orders with timestamps.

### Pizzas Table

pizza_id, pizza_type_id, size, price

- Contains details about each pizza, including size, type, and price.

### Order_Details Table

order_detail_id, order_id, pizza_id, quantity

- Tracks the number of pizzas sold per order.

### Pizza_Types Table

pizza_type_id, name, category, ingredients

- Provides insights into pizza categories and ingredients.

## 📊 Key Insights & SQL Queries

This project answers the following questions:

### Basic Queries:

- Retrieve the total number of orders placed.

- Calculate the total revenue generated from pizza sales.

- Identify the highest-priced pizza.

- Determine the most common pizza size ordered.

- List the top 5 most ordered pizza types.

### Intermediate Queries:

- Find the total quantity of each pizza category ordered.

- order distribution by hour of the day.

- Calculate the average number of pizzas ordered per day.

- Determine the top 3 most ordered pizza types by revenue.

### Advanced Queries:

- Calculate the percentage contribution of each pizza type to total revenue.

- Analyze cumulative revenue trends over time.

- Determine the top 3 most ordered pizza types based on revenue for each pizza category.

## 🛠 Technologies Used

SQL (MySQL) - Data extraction and analysis

DBMS (MySQL Workbench ) - Query execution
