# LITA_CAPSTONE_PROJECT

### Project Title: Sales Performance Analysis for a Retail Store
---
### Project Overview
---
This data analysis aims to generate insight into a Retail store's sales performance over the past year. By analysing the various parameters in the data received, we seek to gather enough insight to make reasonable decisions and determine our data's best performance. 

### Data Sources
---
The primary data source used here is Data Sales.xsl, which is open data that can be freely downloaded from an open source online or any other data repository site.

### Tools Used

- Ms. Excel (for data Cleaning and Analysis )
- SQL Server ( For Querying Data and Analysis)
- Power BI (for Data Visualization)
### Data Cleaning and Preparation

In the initial phase of the Data Cleaning and preparation, the following actions were performed:
1. Data loading and inspection
2. Handling empty variables
3. data cleaning and formatting
### Exploratory Data Analysis

EDA involved exploring of the Data to answer some questions about the Data such as:
- What is the Total Sales by product , Region and Month
- What is the Average Sales per product and total revenue by Region
- What is the Highest-selling Product by total sales value
- What is the total revenue per product
### Data Analysis
---
---SQL
-- The total sales for each product category--

SELECT [Product] , SUM([Total Sales]) AS Total_Sales
FROM[dbo].[SalesData$]
Group By Product
----

---The number of sales transactions in each region--
SELECT [Region] , count( [Total Sales]) AS Total_Sales_Count
FROM[dbo].[SalesData$]
Group By [Region]
---
### Data Visualization

![PIVOT TABLE](https://github.com/user-attachments/assets/6d7a4270-ff19-434e-9973-83d54e4b4f1c)

![Retail store performance](https://github.com/user-attachments/assets/b4858ed3-a7e4-48fe-99d1-dcfe0805ba52)


  
