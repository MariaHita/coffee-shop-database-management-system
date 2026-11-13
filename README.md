# ☕ Coffee Shop Database Management System
### 𓂃 Integrated Database Design & Optimization 𓂃

<p align="center">
  <img src="https://img.shields.io/badge/Database-MySQL-8B5E3C?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Language-SQL-D4A373?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Project-Academic-C9A27C?style=for-the-badge" />
</p>

<p align="center">
  <i>Brewing better business decisions, one query at a time. ☕</i>
</p>

---

## 🌷 About The Project

Welcome to the **Coffee Shop Database Management System!**

This project explores how a well-structured relational database can help improve the operational efficiency of a coffee shop.

From managing daily sales transactions and purchasing activities to monitoring inventory and evaluating staff performance, this project focuses on building an integrated database system that transforms scattered operational data into structured and meaningful information.

Using **SQL and MySQL**, the database is designed through normalization, relational modeling, and automated stock updates to support more consistent data management and better business decision-making.

> ☕ Good coffee deserves good data management!

## 🎯 Project Objectives

The main objectives of this project are:

- Design an integrated relational database to support coffee shop operations.
- Organize sales and purchasing data into structured database tables.
- Apply database normalization from UNF to 3NF.
- Develop an Entity Relationship Diagram (ERD) to visualize database relationships.
- Implement SQL queries and triggers for operational automation.
- Analyze sales, purchasing, inventory, and staff performance data.
- Support business decisions through descriptive data analysis.

## 🛠️ Tools & Technologies

| Tools | Usage |
|:---|:---|
| 🐬 MySQL | Relational Database Management System |
| 💻 SQL | Database creation, manipulation, and querying |
| 🗂️ MySQL Workbench | Database development and visualization |
| 🔗 ERD | Database relationship modeling |
| 📊 Descriptive Analysis | Business performance analysis |

## 🗃️ Database Design

The database design focuses on two major operational processes:

### 01. 🧾 Sales Management

Designed to manage daily coffee shop sales transactions, menu information, and staff performance.

Main entities:
- `Staff`
- `Transaksi`
- `Menu`
- `Pesanan`

### 02. 📦 Purchasing Management

Designed to organize purchasing activities, supplier information, and product procurement records.

Main entities:
- `Supplier`
- `ProdukBeli`
- `Pembelian`
- `TransaksiBeli`

The database uses primary keys and foreign keys to establish relationships between tables and maintain data consistency.

## 🔄 Database Normalization

To create a more organized and efficient database structure, the project applies three normalization stages.

| Stage | Description |
|:---|:---|
| UNF | Identifying unstructured data, redundancy, and anomalies |
| 1NF | Ensuring atomic values in each column |
| 2NF | Eliminating partial functional dependencies |
| 3NF | Eliminating transitive dependencies |

**Why normalization matters:**

- Reduces data redundancy.
- Prevents insertion, deletion, and update anomalies.
- Improves data consistency.
- Creates a more structured relational database.

## 🔍 SQL Implementation & Analysis

This project implements several SQL-based operations and analytical processes.

### 📈 1. Monthly Sales Analysis

Calculates monthly revenue based on the quantity of products sold and their respective prices.

### 🛒 2. Monthly Purchasing Analysis

Analyzes monthly purchasing expenditures to support purchasing evaluation and inventory planning.

### 🏆 3. Best-Selling & Least-Selling Products

Identifies the three highest-selling and lowest-selling products to evaluate product performance and support marketing strategies.

### ⚡ 4. Automated Inventory Management

Implements SQL triggers to automatically update menu stock after an order transaction is recorded.

### 👩‍💻 5. Staff Performance Analysis

Evaluates monthly sales performance to identify employees with the highest sales contribution.

### 🎁 6. Employee Bonus Simulation

Implements a bonus calculation concept by providing an additional IDR 500,000 to the highest-performing staff member each month.

## 📊 Key Findings & Business Insights

Based on the database analysis, several insights were identified:

| Analysis | Results |
|:---|:---|
| 🥇 Highest Monthly Sales | June – IDR 489,500 |
| 🛍️ Highest Monthly Purchasing | November – IDR 4,529,000 |
| ☕ Top-Selling Product | Avocado Coffee Frappe |
| 🍵 Top-Selling Product | Jasmine Green Tea |
| 🥐 Top-Selling Product | Choc Croissant |
| 📉 Lowest-Selling Products | Cappuccino, Matcha Latte, Butter Croissant |

**Staff Performance Insights**

The monthly highest-performing staff members were:

- May: Hivi
- June: Avi
- July: Hivi

These findings can help coffee shop management evaluate product demand, monitor operational performance, and develop better business strategies.

## 🧾 Sales Receipt Prototype

The project also includes a prototype sales receipt to illustrate how transaction data can be presented in a structured format.

The receipt contains:
- Transaction ID
- Transaction date
- Cashier information
- Purchased items
- Item quantities
- Product prices
- Total payment

## 💡 Business Impact

An integrated database system can provide several operational benefits:

| Area | Potential Benefits |
|:---|:---|
| Data Management | More organized and consistent records |
| Sales Monitoring | Easier transaction tracking |
| Inventory Control | Automatic stock updates |
| Purchasing | Better purchasing records |
| Product Evaluation | Identification of popular and less popular products |
| Staff Evaluation | Performance-based monitoring |
| Decision-Making | Data-driven operational insights |

## 👩🏻‍💻 Project Contributors

**Group 4 – Database A**

| Name | Student ID |
|:---|:---|
| Aulia Rahmaeta Octaviani | 5003231009 |
| Maria Immaculata Dyah Hita W. | 5003231027 |
| Ike Maya Setya | 5003231047 |

🎓 **Academic Information**

- Study Program: Statistics
- Department: Statistics
- Faculty: Faculty of Science and Data Analytics
- University: Institut Teknologi Sepuluh Nopember (ITS)
- Course: Database A
- Lecturer: Dr. Muhammad Sjahid Akbar, S.Si., M.Si.

## 🌱 What I Learned

Through this project, I gained experience in:

- Understanding relational database concepts.
- Designing and normalizing database structures.
- Writing SQL queries for data management.
- Building relationships between database entities.
- Applying SQL triggers for automated operations.
- Analyzing operational data to generate business insights.

## 🤎 Final Note

This project represents an exploration of how database technology can support real-world business operations.

By combining structured database design, SQL implementation, and descriptive analysis, coffee shop management can become more organized, efficient, and data-driven.

<p align="center">
  <b>☕ Brew Ideas. Query Data. Create Insights. 🤎</b>
  <br/>
  <i>Made with curiosity, coffee, and SQL.</i>
</p>
