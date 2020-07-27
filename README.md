# Sales-Analysis
Sales Analysis

# DataSet: https://www.kaggle.com/aungpyaeap/supermarket-sales

# About the Dataset:
The growth of supermarkets in most populated cities are increasing and market competitions are also high. The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data.

Attribute information:

 - Invoice id: Computer generated sales slip invoice identification number
 - Branch: Branch of supercenter (3 branches are available identified by A, B and C).
 - City: Location of supercenters
 - Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.
 - Gender: Gender type of customer
 - Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel
 - Unit price: Price of each product in $
 - Quantity: Number of products purchased by customer
 - Tax: 5% tax fee for customer buying
 - Total: Total price including tax
 - Date: Date of purchase (Record available from January 2019 to March 2019)
 - Time: Purchase time (10am to 9pm)
 - Payment: Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet)
 - COGS: Cost of goods sold
 - Gross margin percentage: Gross margin percentage
 - Gross income: Gross income
 - Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)

# Data Cleaning:
- Converting the 'Date' column into datetime data type,
- Adding 'year', 'month' & 'income' columns,
- dropping 'gross income' column, because the value in that column is calculated using the nearest integer value to the 'gross margin percentage' column.

# Data exploration:
In this section we start to look for answers by exploring the data:

The following questions were answered: 
- Question 1: What was the best month for sales? What was the Income & quantity sold in that month?
- Question 2: What City and Branch sold the most product?
- Question 3: What products line are mostly sold?
- Question 4: What products line brought most income and sold most quantity comparable to average price of the product line?
- Question 5: Which gender are most shopaholic?
- Question 6: Does most satisfied customer's spend more?
- Question 7: What payment type is mostly used?
- Question 8: Finding the correlation between the attributes.
