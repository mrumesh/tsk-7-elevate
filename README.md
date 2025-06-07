# tsk-7-elevate
# company : Elevate Labs
# internship : data analytics
** Explanation :
## Task 7: Basic Sales Summary using SQLite and Python

## Objective:
Connect Python to a SQLite database, perform basic SQL queries, and visualize the results with matplotlib. This project simulates a small sales dataset and demonstrates simple sales analysis.

## Tools Used:
- **Python**
- **SQLite3** (in-built)
- **Pandas** (for reading SQL into DataFrame)
- **Matplotlib** (for plotting charts)
- **Jupyter Notebook**

## Files Included:
- `Task ele.ipynb` – The Jupyter notebook with full implementation
- `sales_data.db` – The SQLite database with a `sales` table
- `sales_chart.png` – Bar chart showing revenue by product

## Steps Performed:
1. Created SQLite database (`sales_data.db`) and table `sales`
2. Inserted dummy data with products, quantities, and prices
3. Ran SQL queries using `pandas.read_sql_query()`:
   - Total quantity sold by product
   - Total revenue per product
   - Average price per product
4. Displayed query results using `print()`
5. Plotted revenue by product using matplotlib
