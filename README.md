# Sales_Data_Power_BI_Analysis_Visualization

Cleaning Process https://github.com/aldonaorzol/Sales_Data_Power_Query_Cleaning

<img width="1438" height="808" alt="image" src="https://github.com/user-attachments/assets/815698de-f102-42f8-842f-023230043f01" />


Analysis:

- Sales Channel Structure 'Stacket column chart'- visualizes the contribution of each channel to the final result.

x-axis: category,
y-axis: count of order_ID,
legend: sales_channel,

- Percentage Share of Sales by Category 'Pie chart' - shows the sales structure and the percentage share of each category in the total.

legend: category,
values: sum of amount_zl,

- Percentage of Sales by Channel 'Pie chart' - provides a clear visualization of how total sales are distributed across sales channels.

legend: sales_channel,
values: sum of amount_zl,

- Sales Over the Year 'Stacket area chart' - clearly illustrates monthly sales trends over the course of the year.

x-axis: date - month,
y-axis: sum of amount_zl,

- AVG Basket Value 'Card' - visual enabling users to monitor the average amount spent per order at a glance.

<img width="245" height="92" alt="image" src="https://github.com/user-attachments/assets/81e9f513-87da-4387-a5f6-38217f9156a1" />

- The Best Month 'Card' - visual highlights the best sales month.

<img width="215" height="93" alt="image" src="https://github.com/user-attachments/assets/83970a89-9052-4ec0-9c6e-c571fe22606f" />

- Sales Growth TOP vs AVG 'Card' - visual was chosen to highlight the percentage difference between the best-performing month and the average of all other months. 

<img width="279" height="437" alt="image" src="https://github.com/user-attachments/assets/e2b1742d-ed3e-4ec2-bde4-0b50a0b5bf52" />

- Category/Sales 'Table'- allows users to view exact sales values for each category and easily compare category performance.
Columns: category, sales

- Total Sales Value in 2025 'Stacked bar chart'- compares total sales values across categories, allowing users to identify top-performing categories.

y-axis: category,
x-axis: sum of amount_zl,

- Number of Orders in 2025 'Stacked bar chart'- compares the number of orders across product categories, allowing users to identify the categories with the highest and lowest order volumes.

y-axis: category,
x-axis: count of order_ID,

Auxiliary:

- Sales - The measure calculates total sales revenue by adding together all values from the amount_zl column.

<img width="179" height="40" alt="image" src="https://github.com/user-attachments/assets/e9aa559b-1227-4eba-8a1c-00c5a82e7fe8" />

- YearMonth - The column formats dates as Year-Month (YYYY-MM), enabling monthly aggregation and analysis of sales data.

<img width="317" height="23" alt="image" src="https://github.com/user-attachments/assets/ad617fd1-6649-4018-b81d-5dcf256dc0e2" />

Recommendations:

<img width="1409" height="794" alt="image" src="https://github.com/user-attachments/assets/dd440d8b-63a0-48e9-a029-893d60215253" />

 

