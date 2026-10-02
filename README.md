# Sales_Data_Power_BI_Analysis_Visualization

Cleaning Process https://github.com/aldonaorzol/Sales_Data_Power_Query_Cleaning

<img width="1433" height="803" alt="image" src="https://github.com/user-attachments/assets/3c31f141-85aa-4ac0-9659-87d294b060f4" />

Analysis:
-Sales Channel Structure 'Stacket column chart'- visualizes the contribution of each channel to the final result.
x-axis: category
y-axis: count of order_ID
legend: sales_channel

-Percentage Share of Sales by Category 'Pie chart' - shows the sales structure and the percentage share of each category in the total.
legend: category
values: sum of amount_zl

Percentage of Sales by Channel 'Pie chart' - provides a clear visualization of how total sales are distributed across sales channels.
legend: sales_channel
values: sum of amount_zl

Sales Over the Year 'Stacket area chart' - 
x-axis: date - month
y-axis: sum of amount_zl

AVG Basket Value 'Card' -

AVG Basket Value = 
DIVIDE(
SUM('Tabela'[amount_zl]),
DISTINCTCOUNT('Tabela'[order_ID])
)

The Best Month -
Sales Growth TOP vs AVG
Sales/ Category
Total Sales Value in 2025
Number of Orders in 2025

Business conclusions:

1.	Which category sells best throughout 2025 in terms of sales value and number of orders?

   Charts 'Total Sales Value in 2025' and 'Number of Orders in 2025' shows 
   In terms of sales value, products in the electronics category perform best, whereas products in the beauty category lead in terms of the number of units sold.
3. How did sales in the electronics category change over time?
   Sales remained at a similar level between January and October. The report shows a marked increase in November and December.
4. What is the share of each sales channel in the total annual sales?
   The online store leads with a result of 40.52%, followed by Marketplace at 24.12%. Facebook Ads takes third place with 19.17%, and Google Ads ranks fourth with    15.61%.
5. Which category has the highest average order value, and which has the lowest?
   The "toys and gifts" category recorded the lowest average value, at 116 PLN. The "electronics" category achieved the highest average, at 379 PLN.
6. In which month is a distinct "spike" in sales visible for a given category, and how does it compare to the rest of the year?
   The Home and Garden category shows a clear upward trend during the spring and summer seasons. A seasonal increase can also be observed in the Toys and Gifts category.
7. Does the sales channel structure differ across categories?

   There is no correlation between the category and the sales channel. The report shows no significant differences.

<img width="1409" height="794" alt="image" src="https://github.com/user-attachments/assets/dd440d8b-63a0-48e9-a029-893d60215253" />

 

