# LITA_Class_Documentation

##Project Title: Sales Performance Analysis for a Retail Store

### Project Overview: In this project, you are tasked with analyzing the sales performance of a retail store. You will need to explore sales data to uncover key insights such as top-selling products, regional performance, and monthly sales trends. The goal is to produce an interactive Power BI dashboard that highlights these findings.

### Data Sources:
The primary source of data used here is LITA.capstone Dataset.xlsx . This is an open source data that can be freely downloaded from online source such as Kaggle or any other repository site.

### Tool Used:
Microsoft excel [download here](https://www.microsoft.com)

1, For data cleaning
2, For Analysis 
3.Data visualisation
SQL - Structure Query Languagefor query data
Github  for portfolo Building

### Data Cleaning, Preparation and Transformation
The first phase of data cleaning, preparation and transformation , we carry out the following:action:
1. Data loading and Inspection
2. Handling missing variable
3. 3 Data cleaning and fprmatting.

### Exploratory Data Analysis(EDA)
EDA involved the exploring of the data to answer some question about the dataset such as:
-  What is the top-selling product
 - Regional performance
 - Monthly sales trends
-   Sales overview.

  ###  Data Analysis
  ---
  This is where  we include some basic lines of code or query or even some ofthe DAX expression used  during  your analysis;

     SELECT * FROM SalesData;
    retrieve the total sales for each product category;
    SELECT Product, SUM(Sales) AS TotalSales
     FROM SalesData
     GROUP BY Product


     EXEC sp_rename 'SalesData.TotalSales', 'Sales', 'COLUMN';

      find the number of sales transactions in each region.
       SELECT Region, COUNT(OrderID) AS NumOfTransactions
      FROM SalesData
      GROUP BY Region<img width="501" alt="CUSTOMER DATA" src="https://github.com/user-attachments/assets/eb3ab233-7f51-4488-9bc3-3686878741e0">


      ###Data Visualisation
      

   <img width="491" alt="SALE DATA" src="https://github.com/user-attachments/assets/03cea667-21cf-4e56-8fa4-5207d3e0b128">

<img width="401" alt="Total sale by Product" src="https://github.com/user-attachments/assets/1a99b80d-9c29-4d97-b1e1-7ce37c8e1cc1">
<img width="297" alt="Total sale by Region" src="https://github.com/user-attachments/assets/4633a3d0-c3bf-44fb-9049-be7b2984be12">


