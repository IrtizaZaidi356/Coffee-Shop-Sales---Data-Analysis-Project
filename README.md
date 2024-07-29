# Coffee Shop Sales Data Analysis Project

### Introduction
In the competitive world of coffee shops, understanding sales patterns and customer preferences is crucial for success. This project focuses on analyzing sales data using Microsoft Excel to uncover valuable insights. We will add necessary columns, create pivot tables, apply formulas, and design a dashboard to visualize our findings.

### Data Columns
The dataset includes the following columns:

transaction_id
transaction_date
transaction_time
store_id
store_location
product_id
transaction_qty
unit_price
product_category
product_type
product_detail
Size
Total_Bill
Month Name
Day Name
Hour
Day of Week
Month
Steps for Analysis
### 1. Preparing the Data
Start by ensuring that your data is clean and organized. This includes:

Converting transaction_date to a date format.
Extracting Month, Day, Hour, and Day of Week from transaction_date and transaction_time.
Calculating Total_Bill if not already present using transaction_qty * unit_price.
### 2. Creating Pivot Tables
Pivot tables will help us summarize and analyze the data efficiently. We will create multiple pivot tables to address different questions:

a. Sales by Day of the Week and Hour
Rows: Day Name, Hour
Values: Sum of Total_Bill
b. Monthly Sales Revenue
Rows: Month Name
Values: Sum of Total_Bill
c. Sales by Store Location
Rows: store_location
Values: Sum of Total_Bill
d. Average Price per Order
Rows: transaction_id
Values: Average of Total_Bill
e. Best-Selling Products
Rows: product_id, product_type
Values: Sum of transaction_qty, Sum of Total_Bill
f. Sales by Product Category and Type
Rows: product_category, product_type
Values: Sum of Total_Bill
### 3. Applying Formulas
Use Excel formulas to derive additional insights. For example:

Total Sales Revenue: =SUM(Total_Bill)
Average Order Value: =AVERAGE(Total_Bill)
### 4. Designing the Dashboard
Create a dashboard that visually represents your findings. Include charts and graphs such as:

Line charts for sales trends over time.
Bar charts for sales by store location.
Heat maps for sales by day and hour.
Pie charts for product category sales distribution.
Analysis
Based on the pivot tables and visualizations, we can address the following key questions:

1. How Do Sales Vary by Day of the Week and Hour of the Day?
Analyze the heat map to identify patterns. For example, sales might peak during morning hours on weekdays.

2. Are There Any Peak Times for Sales Activity?
Identify peak times by looking at the highest values in the hourly sales data.

3. What is the Total Sales Revenue for Each Month?
Summarize monthly sales data to understand seasonal trends and plan marketing strategies accordingly.

4. How Do Sales Vary Across Different Store Locations?
Compare sales figures across locations to identify top-performing stores and areas needing improvement.

5. What is the Average Price per Order?
Calculate the average price per order to understand customer spending habits.

6. Which Products are the Best-Selling in Terms of Quantity and Revenue?
Identify top-selling products to optimize inventory and promotions.

7. How Do Sales Vary by Product Category and Type?
Analyze sales distribution across categories and types to tailor offerings to customer preferences.

### Conclusion
By following this guide, you can leverage Excel's powerful data analysis tools to gain actionable insights into your coffee shop's sales performance. The results can help you make informed decisions to drive growth and enhance customer satisfaction.


![coffeeshop](https://github.com/user-attachments/assets/c2f0a1bc-f8ef-4de6-903d-25c7c39a329a)
