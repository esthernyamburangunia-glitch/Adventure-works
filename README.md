Adventure Works Sales & Business Intelligence Dashboard (Power BI)
Overview

This project presents an end-to-end Business Intelligence solution built using Microsoft Power BI and the Adventure Works sample dataset. The dashboard transforms raw business data into meaningful insights that support strategic decision-making across sales, customers, products, and geographic performance.

The project demonstrates the complete Power BI workflow, including data preparation, data modeling, DAX calculations, visualization design, and interactive reporting.

Project Objectives

The primary objectives of this project were to:

Analyze overall sales performance and profitability.
Monitor key business performance indicators (KPIs).
Identify top-performing products and product categories.
Understand customer purchasing behavior.
Compare regional sales performance.
Build an interactive dashboard for business users.
Dataset

The project uses the Adventure Works sample database provided by Microsoft.

The dataset contains information on:

Sales Orders
Customers
Products
Product Categories
Sales Territories
Dates
Resellers (if applicable)
Tools & Technologies
Microsoft Power BI Desktop
Power Query Editor
DAX (Data Analysis Expressions)
Data Modeling
Microsoft Excel / CSV (data source)
Data Preparation

The following transformations were performed using Power Query:

Removed duplicate records
Corrected data types
Renamed columns for readability
Removed unnecessary fields
Handled missing values
Created a clean and optimized data model
Established relationships between fact and dimension tables
Data Model

A Star Schema was implemented to improve performance and simplify reporting.

Fact Table
FactInternetSales
Dimension Tables
DimDate
DimCustomer
DimProduct
DimProductCategory
DimProductSubcategory
DimSalesTerritory
DimGeography
DAX Measures

Several DAX measures were created, including:

Total Sales
Total Orders
Total Profit
Profit Margin %
Average Order Value
Total Customers
Year-to-Date Sales (YTD)
Previous Year Sales
Sales Growth %
Running Total Sales
Dashboard Features

The dashboard includes interactive visualizations such as:

Executive KPI Cards
Sales Trend Analysis
Sales by Product Category
Top Selling Products
Sales by Country/Region
Customer Segmentation
Monthly and Yearly Sales Performance
Profit Analysis
Interactive Filters (Slicers)
Drill-through Pages
Tooltips for additional insights
Key Business Insights

Some of the insights generated include:

Identification of the highest revenue-generating products.
Comparison of sales performance across different regions.
Seasonal sales trends and demand patterns.
Customer purchasing behavior over time.
Contribution of product categories to overall revenue.
Profitability analysis across different product lines.
## Dashboard Preview

### Executive Dashboard

![Executive Dashboard](https://github.com/esthernyamburangunia-glitch/Adventure-works/blob/main/Images/Screenshot%202026-07-21%20211820.png)
