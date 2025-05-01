# TASK-7-Get-Basic-Sales-Summary-from-a-Tiny-SQLite-Database-using-Python

# Sales Data Summary with SQLite and Python

## Overview

This project demonstrates how to:
- Load sales data from a CSV file (`sales_data_sample.csv`)
- Store the data in a SQLite database using Python
- Run SQL queries to summarize sales by product line (total quantity and revenue)
- Display the results and visualize revenue by product line with a bar chart

## Steps Performed

1. **Data Loading:**  
   The script reads `sales_data_sample.csv` using pandas, handling possible encoding issues.

2. **Data Preparation:**  
   Only the relevant columns (`PRODUCTLINE`, `QUANTITYORDERED`, `PRICEEACH`) are selected and renamed for clarity.

3. **Database Creation:**  
   A SQLite database (`sales_data.db`) is created. The cleaned data is inserted into a table called `sales_data_sample`.

4. **SQL Query:**  
   Using SQL, the script calculates the total quantity sold and total revenue for each product line.

5. **Results Display:**  
   The summary table is printed, and a bar chart of revenue by product line is plotted using matplotlib.

## Requirements
- Python
- pandas
- matplotlib
- sqlite3(python inbuilt)
