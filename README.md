# Analysis of bike store sales over three yeers:2016,2017 and,2018
# Business Problem 
The business noticed that some stores were generating significantly lower sales compared to other branches.
# Goal
The goal of the analysis was to identify the reasons behind this underperformance and provide data-driven recommendations to improve sales.
# Storytelling
## Overview
## Identify the Problem
- Which stores have the lowest sales performance?
-  How does sales performance vary across stores?
-  hich stores are underperforming compared to the company average?
-  Is the sales decline consistent over time or recent?
## Orders Investigation
-  Do underperforming stores have fewer orders?
-  What is the average order value per store?
-  Is the issue caused by low order volume or low order value?
## Customer Investigation
- Do low-performing stores have fewer customers?
- What is the average revenue per customer in each store?
- Are customers returning to buy again in these stores?
- Which stores have the highest customer retention?
## Product Investigation
-  Which products are driving sales in high-performing stores?
-  Are those products available in low-performing stores?
-  Which product categories have low sales in these stores?
-  Are high-demand products underrepresented in certain stores?
## Staff Investigation
-  Which staff members generate the highest sales?
-  Do underperforming stores have lower staff performance?
-  How does sales per staff compare across stores?
## Insights & Recommendations
## Analysis Steps 
## Data Collection
Extract Data From BIKESTORES Database 
Extract 5 Tables are Orders, Customers , Products, Store and staff.  
Tool: SQL, SQL server 
## Data Preprocessing 
Clean and prepare the collected data by removing duplicates rows 
Tool: Power Query 
## Data Modeling 
Designing a star schema to organize data into one fact and 6 dimension tables. This improves query performance and enhances ease of analysis
## Data Analysis 
identify trends, patterns, and correlations within the sales data
Tool: DAX 
## Data Visualization
Create charts, graphs, and dashboards to visually represent the data. Visualization aids in quickly identifying key insights and making the data more accessible to stakeholders.
Tool: Power BI Visuals 
  ## DASHBOARD
![Region](https://github.com/Saragamil3/Bike-Store-Sales-Analysis/blob/main/Screenshot%202024-08-08%20072619.png)
![Sales](https://github.com/Saragamil3/Bike-Store-Sales-Analysis/blob/main/Screenshot%202024-08-08%20072703.png)
![Products](https://github.com/Saragamil3/Bike-Store-Sales-Analysis/blob/main/Screenshot%202024-08-08%20095451.png)
![Region](https://github.com/Saragamil3/Bike-Store-Sales-Analysis/blob/main/Screenshot%202024-08-08%20073857.png)


## Key Results 
- Total Sales   8.58M
- Net Sales   7.69M
- Discount Percentage  10.37%
- Total Orders   1615
- Units Sold    4722
- Monthly Orders  56 in 2016 , 57 in 2017 and, 24 in 2018
- Sales Growth Rate 
- Average Purchase Value    5.36K
- Average Of Delivery Duration is 2 days
- Maximum Shipping Delay is 2 days
- Percentage of Delay in Orders    28%
- Most Store in terms of sales is "Baldwin Bikes"
- Most state in sales and Count of Customers is "NY"  
- Top Sales Person in terms of Sales is  "Marcelene Boyer" 
- In the last 7 Months of 2018, sales decreased by 66.8% compared to previous years due to a decline in the number of orders during this period.
- Most brand name in terms of sales is "Trek" and, Category name is "Mountain Bikes" and "Cruisers Bicycles" in terms of orders





