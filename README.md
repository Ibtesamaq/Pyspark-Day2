# Customer Purchase Analytics with PySpark

This mini-project demonstrates how to use **PySpark** to perform analytical operations on customer and transaction datasets. It covers essential data engineering techniques such as **DataFrame joins** and **window functions** for grouped computations and rankings.

##  Joins Covered
- Inner Join
- Left Join
- Right Join
- Anti Join

##  Window Functions Used
- `row_number()`
- `rank()`
- `dense_rank()`

##  Task Performed
The project begins by joining customer and transaction datasets using various join types. We then use window functions to extract the **latest transaction per customer** using `row_number()` and rank products by **total revenue within each category** using `dense_rank()`. This allows for customer-specific insights and category-based product performance analysis.

##  Files
- `customer_data.csv`
- `transaction_data.csv`
- `customer_transaction_data.csv` (merged)
- `analytics_script.py` (main logic)

##  Tech Stack
- Python
- PySpark
- Pandas (for preview)
