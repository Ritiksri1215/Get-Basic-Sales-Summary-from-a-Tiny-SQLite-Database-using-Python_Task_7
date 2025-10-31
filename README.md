# Get-Basic-Sales-Summary-from-a-Tiny-SQLite-Database-using-Python_Task_7

https://colab.research.google.com/drive/1UP1u9UWPmddOWy3LF-gE_Zf1FjW8SYxN?usp=sharing

Objective:

Use SQL inside Python to pull simple sales info (like total quantity sold and total revenue)  
and display it using print statements and a basic matplotlib bar chart.

Tools & Libraries Used:

*Python 3*
*SQLite (sqlite3)*
*Pandas*
*Matplotlib*

Dataset:

A small SQLite database named *sales_data.db* was created with one table:  
sales (id, product, quantity, price)

Sample data:

| Product | Quantity | Price |
|----------|-----------|--------|
| Laptop | 5 | 60000 |
| Mouse | 20 | 500 |
| Keyboard | 10 | 1500 |
| Monitor | 7 | 12000 |
| Headphones | 15 | 2000 |

Steps Performed:

1. Connected Python to SQLite using sqlite3.connect("sales_data.db")
2. Created a table named sales and inserted sample records
3. Run an SQL query
