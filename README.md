# Basic Sales Summary using MySQL and Python

# Objective
The goal of this task is to connect Python with a MySQL database, retrieve basic sales data using SQL queries, and visualize the results using a simple bar chart in Jupyter Notebook.

---

# Tools & Technologies
- **Python*
- **Jupyter Notebook*
- **MySQL Workbench / MySQL Server*
- **Libraries:* `mysql-connector-python`, `pandas`, `matplotlib`

---

# Dataset
A small MySQL table named `sales` was created with the following structure:

| id | product     | quantity | price  |
|----|--------------|----------|--------|
| 1  | Laptop       | 5        | 70000  |
| 2  | Mouse        | 20       | 500    |
| 3  | Keyboard     | 15       | 1500   |
| 4  | Monitor      | 7        | 12000  |
| 5  | Headphones   | 10       | 2000   |

---

# Steps Performed

1. **Created Database and Table* in MySQL Workbench:
   - Database: `sales_db`
   - Table: `sales`
   - Inserted sample sales data.

2. **Connected to MySQL* using `mysql.connector` in Python.

3. **Executed SQL Queries:*
   - Calculated total quantity sold and total revenue.
   - Computed revenue by product.

4. **Displayed Results* using `pandas` DataFrames.

5. **Visualized Data* with a simple bar chart using `matplotlib`.

---

# Output Example

**Sales Summary:*
total_quantity_sold total_revenue
0 57 407500.0

*Revenue by Product:*
| Product | Revenue (₹) |
|----------|-------------|
| Laptop | 350000 |
| Monitor | 84000 |
| Keyboard | 22500 |
| Headphones | 20000 |
| Mouse | 10000 |

*Bar Chart:*  
Displays each product’s revenue visually.

---

# Project Files

| File | Description |
|------|-------------|
| `TASK7_Sales_Summary.ipynb` | Main Jupyter Notebook with code and outputs |
| `README.md` | Project documentation |
| `sales_data.sql` | SQL file to create and populate the table |

---

Jay Shankar Giri
Aspiring Data Analyst | BCA, New Horizon College, Bengaluru
Skills: Python | Power BI | Excel | MySQL | Data Visualization
