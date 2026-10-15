# Business Intelligence Dashboard

## Project Overview
This project was developed as part of a Business Intelligence and Data Analytics portfolio project.
Carried out data cleaning and analysis using Power BI on a retail company with the end goal being to help management make better business decisions.

## Business Problems 
these were the questions that needed clarification while I was building my dashboard on power bi;

- State generating the highest revenue
- Category generating the highest revenue
- Total Revenue
- Previous Month Revenue
- MoM Growth%
- Total Orders
- Unique Customers
- Average Order Value
- What happened to revenue compared with the previous month?
- Which state is performing best?
- Which category is performing best?
- What is the overall business story?
- and What should management investigate based on my findings?

## Tools and Technologies 
Tools used for the project: 

- Power BI
- Power Query
- and DAX were used for the project

## Datasets 
These are important information about business sales transactions; key fields include 

- Customer ID
- Customer Name
- Product ID
- Product Name
- Brand
- Category
- State
- Branch
- Order Date
- Order ID
- Order Status
- Net Sales
- Sales Target

## Data Model 
The following were the models used for the project: 

- Fact Expenses (Amount, Amount Status, Department, Employee ID, Expense Date, Expense ID, Expense Type)
- Fact Inventory (Closing Stock, Date, Inventory ID, Opening Stock, Product ID, Reorder Level, Stock In, Stock Out, Warehouse)
- Fact Sales (Channel, Customer ID, Discount, Discount Amount, Employee ID, Gross Sales, Net Sales, Order Date, Order ID, Order Status, Payment Method, Product ID, Quantity, Unit Price)
- Fact Targets (Customer Target, Employee ID, Sales Target, Target ID)
- Dimension Tables include
  - Dim Customers
  - Dim Date
  - Dim Employees
  - and Dim Products

## Data Preparation 
Data was prepared using Power Query. Preparation process included 

- Importing the raw data
- Cleaning missing values
- Removing duplicates
- Correcting data types
- Standardizing text values
- Creating calculated values where necessary

## Key Dax Measures 
Some of the measures created for the dashboard includes 

- Total Revenue
- Total Sales
- Total Quantity
- Total Cost
- Total Profit
- Total Order
- Total Customers
- Average Order Value
- Average Quantity Per Order
- Profit Margin
- Sales Achievement
- Sales Growth
- Sales Target
- and Sales Variance
