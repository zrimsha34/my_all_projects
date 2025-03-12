# Fast Food Management System (SQL)

## 📌 Project Overview
This project is a **Fast Food Management System** built using SQL. It includes database schema design, relationships, and CRUD operations for managing categories, products, customers, sales, employees, and orders.

## 📂 Database Structure
The database consists of the following tables:

- **CATEGORY** – Stores food categories (e.g., Burgers, Beverages).
- **PRODUCT** – Contains menu items with prices and category references.
- **CUSTOMER** – Stores customer details.
- **SALE** – Records food sales transactions.
- **EMPLOYEE** – Maintains employee roles and salaries.
- **ORDERS** – Tracks customer orders and employee handling them.

## 🔗 Relationships
- **PRODUCT** references **CATEGORY** using 'C_ID'.
- **SALE** references **CUSTOMER**, **CATEGORY**, and **PRODUCT**.
- **ORDERS** references **CUSTOMER** and **EMPLOYEE**.

## 🚀 How to Use
1. **Download the SQL file** or clone the repository.
2. Open **MySQL Workbench** or any SQL database tool.
3. Create a new database (e.g., 'fast_food_db').
4. Run the SQL file to create tables and insert data.

## 📝 Notes
- The database is designed for **MySQL**.
- Views ('CATEGORY1', 'PRODUCT1', etc.) are created for easier data retrieval.
- `ON DELETE CASCADE` is used to maintain referential integrity.

## 📎 Repository Link
[GitHub Repository](https://github.com/zrimsha34/my_all_projects/tree/main/SQL)

