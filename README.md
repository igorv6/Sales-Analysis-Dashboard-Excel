# Sales-Analysis-Dashboard-Excel
First Sales Analysis Dashboard using Excel
This is my first analysis project using Excel. I got the sales data from Kaggle using the following link https://www.kaggle.com/datasets/samruddhi4040/online-sales-data.

Below there are the steps that I follow during my analysis:

# Step 1: Getting the data
For my first Project I decided to analyze the Sales of an Indian Store for 2018 year. There are 2 dataset: Orders and Details.
Orders Table contain information about the orders, there are columns with the Order ID, Order Date, and information about Customers (Name,State and City).
Details Table contains information details about the orders received: Amount,Category,Sub-Cateogry and Payment Mode. Both Table contain the Order ID.

# Step 2: Observe the data and make sure all is good
Our data is in CSV file format so I used Power Query to import and clean the data. After having finishing checking
cleaning the data,I load the dataset into the Excel worksheet. Since we have another dataset, I repeat the step again. To combine and analyze the two tables I used Power Pivot.

# Step 3: Defining Business questions 
Before analyzing them, I need to define what I want to find. below are my  business questions for my analysis:
1) How much is the amount of sales for each month?
2) What are the profit for each month?
3) How many products were sold each month?
4) What type of payment method is preferred by customers?
5) Which products have sold the most?
6) What are the top 3 profictable products?

# Step 4: Analyzing data  
I start my analysis using Pivot Table, with which I can obtain valuable insights from the sales data.
I got Total Sales, Total Profit and Number of Product Sold. After that, I find insights for my business questions.

![image](https://github.com/user-attachments/assets/ce059c5d-af51-42f8-b455-da0d3e69bc68)

Total Sales for 2018 $437.771 - Profit reaches the amount of $36.963 - Total Quantity sold 5615 unit
1) From the Pivot Table "Sales per Month" we see the sales for each month, January is the month with more amount of sales $61.632 followed by March with $60.632.
   July is the month with less sales $12.966 followed by June with $23.658.
2) Profit per Month see January as the month with more Profit $9.684 followed by February $8.684 and March $7.793. There are some months that showed negative profit: May -$3.730,
   July -$2.138, December -$1.604 and September -$1.399.
3) March is the month with most sold units (751) followd by January (745) and February (751). July,September and May are the months with less unit sold.
4) With a total of 1500 transaction, Cash on Delivery (COD) is the most frequent payment method used by customers, followed by Unified Payments Interface (UPI) with 331 transactions
6) For the Product sold, we see that Saree is the most type of product sold with 795 unit/year followd by Hankerchief 741 unit/year and Stole 671 unit/year.
7) The 3 profictable products are: Printers with $8.606 of profit, Bookcases with $6.516 and Saree with $4.057

# Step 5: Data Visualization
Once the analysis is complete, it's time to proceed crating a dashboard to visualize and communicate the findings and insights we have gained. 
Using the dashboard I can provide and easy-to understand overview of the performance, trend and other important information.

![image](https://github.com/user-attachments/assets/6fd9ac28-2583-4010-879c-6639122d88b5)

# Step6: Recommendations
1) Seeing the total sales and total profit, we can calculate the margin profit that is 8.44% and is relatively low. Thsi store need to concentrate is effort to evaluate competitors and operation
   operation costs. May,July,December and September showed negative profit, They need to focus on these months to see what happened and if there are some problems occured during thse months.
2) Since July, September and May are the months with less unit sold. they need to create a better marketing strategies to increase the sales.
3) Cash on Delivery is the most frequent payment method, The Store must following to allow this method of payment. If they want to increase the use of other payment, the store has to offer incentives
   or discount to increase the use of other payment method
4) Printers,Bookcases and Sare are the core product of the store. They need to continue focus on this product, maybe consider to expand the collection of these popular products.
   On the other hand, they could reducing the stock of the less profictable products.





