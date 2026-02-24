# 📊 CRM System Project (MySQL)

## 📌 Project Overview
This project is a **Customer Relationship Management (CRM) System** built using **MySQL**.  
The system helps manage customer data, sales information, and business interactions in a structured database.

This project demonstrates SQL skills such as:
- Table Creation
- Joins
- Aggregations
- Data Analysis Queries

---

## 🎯 Objectives

- Store customer information
- Track orders and sales
- Manage products
- Analyze business performance
- Generate reports using SQL

---

## 🛠️ Technologies Used

- MySQL
- SQL
- MySQL Workbench

---

## 📂 Database Tables

### Customers Table

| Column Name | Description |
|-----------|-------------|
| customer_id | Unique customer ID |
| customer_name | Customer name |
| email | Customer email |
| phone | Contact number |
| city | Customer location |

---

### Products Table

| Column Name | Description |
|-----------|-------------|
| product_id | Product ID |
| product_name | Product name |
| price | Product price |

---

### Orders Table

| Column Name | Description |
|-----------|-------------|
| order_id | Order ID |
| customer_id | Customer ID |
| order_date | Order date |
| total_amount | Total order amount |

---

### Sales Table

| Column Name | Description |
|-----------|-------------|
| sale_id | Sale ID |
| order_id | Order ID |
| product_id | Product ID |
| quantity | Quantity sold |

---

## 🔍 SQL Concepts Used

- CREATE TABLE
- INSERT INTO
- SELECT
- WHERE
- GROUP BY
- ORDER BY
- JOIN
- Aggregate Functions
  - SUM()
  - COUNT()
  - AVG()

---
## 📊 Example Queries

### Total Sales by Customer

```sql
SELECT c.customer_name,
       SUM(o.total_amount) AS total_sales
FROM customers c
JOIN orders o
ON c.customer_id = o.customer_id
GROUP BY c.customer_name;
```
---

## 📈 Project Features

- Customer Management
- Order Tracking
- Sales Analysis
- Business Reports
- Data Organization

---

## 💡 Skills Demonstrated

- SQL Queries
- Database Design
- Data Analysis
- Joins (INNER JOIN)
- Aggregate Functions (SUM, COUNT, AVG)
- GROUP BY and ORDER BY
- Data Filter
---

## 🚀 How to Run the Project

1. Install MySQL Server
2. Open MySQL Workbench
3. Create a new database

```sql
CREATE DATABASE crm_system;
USE crm_system;
```
---

## 👩‍💻 Author

**Preethi**

Aspiring **Data Analyst**

### Skills

- Python
- SQL
- Excel
- Tableau
- Power BI



