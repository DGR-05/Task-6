# Task-6

#  Objective:

Analyze monthly sales performance by summarizing revenue and order volume over time.

SQL Components Used:

USE sales;

➤ Selects the database to work in.

SELECT order_id, order_date FROM sales;

➤ Checks raw order data for structure and validation.

EXTRACT(YEAR FROM order_date), EXTRACT(MONTH FROM order_date)

➤ Extracts the year and month from the order date to group data by time period.

GROUP BY year, month

➤ Aggregates data to a monthly level.

SUM(price)

➤ Calculates total revenue for each month.

COUNT(DISTINCT order_id)

➤ Counts how many unique orders occurred each month (volume).

ORDER BY year, month

➤ Sorts the output chronologically.

#  DATASET - SALES

![Screenshot 2025-06-11 130652](https://github.com/user-attachments/assets/beecc59a-ab9e-433b-9737-36a61460a690)
