## Northwind Traders SQL Analysis

This project explores the **Northwind Traders** database using SQL. The goal is to analyze business data, understand table relationships, and extract insights using SQL queries.

### Dataset
The **Northwind Traders** dataset is a sample database representing a fictional company that imports and exports specialty foods. It includes tables for customers, orders, employees, suppliers, and products.

### Project Overview
- Connected to PostgreSQL using 'ipython-sql'
- Explored database schema and table relationships
- Wrote SQL queries for various business insights, such as:
  - Sales trends
  - Best-selling products
  - Top customers by revenue
  - Employee order performance

### Files Included
- **`northwind_analysis.ipynb`** - Jupyter Notebook with SQL analysis
- **`northwind.sql`** - Database

### Setup Instructions
1. Install PostgreSQL and create a database.
2. Import the Northwind database:
   psql -U your_user -d your_database -f northwind.sql
3. Install required Python packages:
   pip install ipython-sql psycopg2
4. Run the Jupyter Notebook to explore the data
