# 🛒 E-Commerce Sales & Analytics System

## 📌 Project Overview
This project is a complete SQL-based E-Commerce Sales & Analytics System developed using MySQL.  
It manages customer data, product inventory, orders, and payment information while generating valuable business insights through SQL queries.

---

# 🚀 Features
✅ Customer Management  
✅ Product Inventory Tracking  
✅ Order Management  
✅ Payment Status Monitoring  
✅ Revenue Analysis  
✅ Sales Reporting  
✅ Top Selling Product Analysis  
✅ Low Stock Detection  

---

# 🛠️ Tools & Technologies
- MySQL
- SQL

---

# 🗄️ Database Tables
| Table Name | Description |
|------------|-------------|
| CUSTOMERS | Stores customer information |
| PRODUCTS | Stores product details and stock |
| ORDERS | Stores customer orders |
| PAYMENTS | Stores payment information |

---

# 📊 SQL Concepts Used
- CREATE DATABASE
- CREATE TABLE
- INSERT INTO
- SELECT Statements
- INNER JOIN
- GROUP BY
- ORDER BY
- Aggregate Functions
- WHERE Clause

---

# 📈 Reports Generated
### 🔹 Customer Purchase Report
Displays customer purchases with product details.

### 🔹 Total Revenue Report
Calculates total business revenue.

### 🔹 Top Selling Products
Shows the most sold products.

### 🔹 Pending Payment Report
Displays pending payments.

### 🔹 Premium Products Report
Shows high-value products.

### 🔹 Low Stock Products
Identifies products with limited stock.

### 🔹 International Customers
Displays customers from international cities.

---

# 💻 Sample SQL Query

```sql
SELECT PRODUCTS.PRODUCT_NAME,
       SUM(ORDERS.QUANTITY) AS TOTAL_SOLD
FROM ORDERS
INNER JOIN PRODUCTS
ON ORDERS.PRODUCT_ID = PRODUCTS.PRODUCT_ID
GROUP BY PRODUCTS.PRODUCT_NAME
ORDER BY TOTAL_SOLD DESC;
```

---

# 🎯 Project Outcome
This project demonstrates practical SQL skills including:
- Database Design
- Data Management
- SQL Joins
- Business Data Analysis
- Reporting & Insights Generation

---

# 📌 Project Status
✅ Completed
