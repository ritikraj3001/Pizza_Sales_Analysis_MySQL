# 🍕 Pizza Sales Analysis Using SQL

An end-to-end SQL project focused on analyzing pizza sales data to uncover business insights related to revenue, customer ordering behavior, product performance, and sales trends.

This project demonstrates SQL skills ranging from basic aggregation queries to advanced analytical techniques using joins, window functions, and cumulative calculations.

---

## 📌 Project Overview

The objective of this project is to analyze pizza sales data and answer important business questions such as:

- How much revenue does the business generate?
- Which pizzas contribute the most to sales?
- What are customers' ordering patterns?
- Which pizza categories perform best?
- How does revenue grow over time?

The project covers **Basic**, **Intermediate**, and **Advanced SQL queries** to simulate real-world business analysis scenarios. :contentReference[oaicite:0]{index=0}

---

## 🎯 Business Problem

A pizza restaurant wants to better understand its sales performance and customer preferences in order to:

- Increase revenue
- Improve inventory planning
- Optimize menu offerings
- Identify best-selling products
- Improve operational efficiency

This analysis helps management make data-driven decisions based on historical sales data.

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| SQL | Data Analysis |
| MySQL | Database Management |
| Excel/CSV | Data Source |
| PowerPoint/PDF | Project Presentation |

---

## 📂 Dataset Information

The project uses four relational datasets: :contentReference[oaicite:1]{index=1}

| Table Name | Description |
|-----------|-------------|
| `orders` | Customer order information |
| `order_details` | Quantity of pizzas ordered |
| `pizzas` | Pizza size and pricing details |
| `pizza_types` | Pizza category and ingredients |

The database schema follows a relational model connected through primary and foreign keys. :contentReference[oaicite:2]{index=2}

---

## 🗄️ Database Schema

```text
orders
│
├── order_id (PK)
├── order_date
└── order_time

order_details
│
├── order_details_id (PK)
├── order_id (FK)
├── pizza_id (FK)
└── quantity

pizzas
│
├── pizza_id (PK)
├── pizza_type_id (FK)
├── size
└── price

pizza_types
│
├── pizza_type_id (PK)
├── name
├── category
└── ingredients

```

## SQL Concepts Covered
### SQL Fundamentals
SELECT
WHERE
ORDER BY
GROUP BY
HAVING
LIMIT

## Intermediate SQL
INNER JOIN
Multiple Table Joins
Aggregate Functions
Date Functions
Subqueries

---

## 💡 Business Insights
Certain pizza categories generate a significant share of revenue.
Customer ordering behavior changes throughout the day.
A small number of pizza types contribute a large portion of total revenue.
Revenue trends help identify seasonal demand patterns.
Understanding customer preferences can improve inventory management.
