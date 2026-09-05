# Racheal-portfolio-
Data Analyst Portfolio

# [project 1: Excel Cleaning & Functions - TS Academy
# Excel Data Cleaning & Analysis | TS Academy
## Overview
This was my first practical Excel assignment completed during my Data Analytics training at TS Academy.
The project focused on working with an employee dataset and applying essential Excel techniques for data formatting, text manipulation, data cleaning, and analysis.

## Skills Demonstrated

- Data Formatting
- Data Cleaning
- Text Functions
- Aggregate Functions
- Conditional Calculations
- Employee Data Analysis

## Excel Functions Used
LEFT
RIGHT
LEN
UPPER
LOWER
PROPER
TRIM
SUM
AVERAGE
COUNTA
SUMIF
AVERAGEIF
SUMIFS
AVERAGEIFS
COUNTIFS
MAXIFS

## Tasks Completed 
![Dashboard Screenshot](https://github.com/oyelakinracheal213-netizen/Racheal-portfolio-/commit/68d2942292d35ec6ec29f8eef97a309a3a286fe8)

### Data Formatting
- Formatted table headers
- Added table borders
- Applied header-row formatting
- Formatted monthly salary as currency

### Text Manipulation & Cleaning
- Extracted first and last names
- Created employee email addresses
- Calculated full-name length
- Standardized department names
- Removed unnecessary spaces

### Data Analysis
- Calculated total and average salary
- Counted employees
- Analyzed salaries by department
- Analyzed employees by location, gender, and experience
- Calculated maximum salary for the IT department
- 
## Learning Outcome
This project strengthened my foundation in Excel and gave me practical experience cleaning employee data and using formulas to answer specific analytical questions.




## Sales Performance Dashboard (Excel)
## Project Overview
This project is an end-to-end Sales Analysis built in Microsoft Excel. I started by cleaning and transforming the raw dataset using Power Query, then used PivotTables, PivotCharts, and slicers to create an interactive dashboard that summarizes performance across products, sales reps, cities, and months. The final dashboard helps stakeholders track results quickly and make data-driven decisions.

## Objectives
Clean and prepare the dataset (using Power Query) for accurate reporting  
Calculate key KPIs: Revenue, COGS, Profit, and Customers  
Identify:  
Most profitable product  
Top-performing sales rep by revenue  
City with the highest COGS  
Worst-performing month by customer count  
Build an interactive dashboard with slicers for fast filtering and insight generation

## Data Cleaning & Transformation (Power Query)
Before building the dashboard, I cleaned the dataset using Power Query to ensure consistency, accuracy, and analysis-readiness. Key steps included:  
Removed errors and handled missing values where necessary  
Checked for duplicates and ensured records were consistent  
Standardized data types (e.g., Date, numbers)  
Cleaned and standardized text fields (e.g., Product, City, Region, Category)  
Validated calculated fields to ensure reliable KPI outputs  
Loaded the cleaned table back into Excel for PivotTable analysis  

## Dataset
The dataset contains sales transactions with fields such as:  
Date, Region, City, Customer Type, Channel  
Product, Category, Unit Price, Quantity  
Sales Rep, Revenue, COGS, Profit  

## Tools Used
Microsoft Excel
Power Query (data cleaning & transformation)  
PivotTables  
PivotCharts  
Slicers  
Dashboard design and formatting

## Key KPIs (Overall)
Total Revenue: 2.33B  
Total COGS: 1.86B  
Total Profit: 465.7M  
Total Customers: 2,098 

## Dashboard Features
The dashboard includes:  
Product Profit Analysis (to identify the highest-profit product)  
Revenue by Sales Representative  
COGS by City  
Monthly Customer Trend  
Slicers for filtering by:  
Region  
Category 

## Key Insights
May was the lowest-performing month (customers)  
Peter generated the highest revenue  
Lagos recorded the highest cost (COGS)  
Laptop A13 drove the highest profit  


## Power BI Sales Performance Dashboard
## Project Summary
This project delivers a complete Sales Performance BI report built in Power BI—from raw data to an interactive, insight-driven dashboard. I used Power Query to clean and standardize the data, designed a star-schema data model (fact + dimension tables), created KPI measures in DAX, and built a multi-page report that enables stakeholders to monitor revenue performance, identify top drivers, and explore customer and product trends using slicers.

## Business Questions Answered
This report was designed to help answer questions such as:  
What is the total revenue, order volume, and average order value?  
How is revenue trending over time, and how does it compare year-over-year (YoY)?  
Which regions and categories contribute most to revenue?  
What are the top-performing products and their cost vs revenue relationship?  
Which customers and segments generate the highest revenue?  
What portion of transactions are returns, and how do returns affect performance?

## Tools & Skills Used
## Power BI Desktop
Power Query (ETL: cleaning, transformation, validation)
Data Modeling (relationships, star schema)
DAX (measures/KPIs and time intelligence)
Report Design (multi-page layout, interactivity, slicers)

## Data Preparation (Power Query)
To ensure the analysis was accurate and consistent, I performed structured data-cleaning and transformation steps, including:  
Standardized and cleaned date fields to support time-based analysis  
Cleaned text fields (trimmed extra spaces and standardized formatting)  
Reviewed and standardized region values to reduce geographic reporting inconsistencies  
Converted key numeric fields (e.g., Unit Price) to correct data types  
Validated Quantity as whole numbers and reviewed negative quantities to isolate returns  
Reviewed missing/blank values and handled them where appropriate  
Checked for duplicate records and removed unnecessary blank rows  
Reviewed Discount values to ensure they were suitable for revenue calculations  
Created a transaction-level Revenue field using Quantity, Unit Price, and Discount  
Built a dedicated Date Table to support time intelligence and YoY analysis

## Data Model (Star Schema)
A scalable model was created to ensure accurate filtering and performance reporting:  
Fact Table: Transactions (sales records)  
Dimension Tables:  
Products (category, unit cost, product details)  
Customers (customer attributes, segment, join date)  
Date Table (calendar structure for trends and YoY)
This structure improves report accuracy, enables clean drilldowns, and supports reliable time-based calculations.

## KPI Logic (Business Rules & Measures)
Key measures were defined to reflect real business logic:  
Revenue: calculated using Quantity, Unit Price, and Discount at transaction level  
Total Revenue: sum of transaction revenue  
Total Orders: distinct count of Transaction IDs  
Total Units Sold: sum of Quantity  
Average Order Value (AOV): Total Revenue ÷ Total Orders  
Return Rate: returned transactions as a proportion of total transactions  
YoY Revenue Growth: compares current period revenue to the same period in the previous year  
Negative quantities were evaluated alongside OrderStatus to distinguish returns from potential data issues

## Report Pages & Key Features
1) Executive Overview
KPI cards: Return Rate, AOV, Total Revenue, Total Orders  
Revenue trend over time  
Revenue by category  
Revenue by region  
Slicers: Region, Year, Category  
2) Product Performance
Top products (Top 5)  
Revenue by category analysis  
Cost vs Revenue comparison to support margin-related discussion  
3) Customer & Segment Analysis
Top customers by revenue  
Revenue by region (customer lens)  
Revenue split by customer segment  
4) Data Quality Notes
A dedicated page documenting data cleaning steps and KPI logic for transparency and auditability

## Key Outcomes / Insights (High-Level)
Clear visibility into revenue performance and trend behavior over time  
Identified top revenue contributors by region, category, and product  
Highlighted customer concentration through a ranked view of top customers  
Included return-awareness by incorporating return rate and return logic into KPIs  
Improved trust in reporting through a documented data quality and transformation process


## Business Analytics Dashboard (Power BI) — TS Academy Final Project
## Project Overview
This project is my final capstone project at TS Academy, where I built a complete Business Analytics Dashboard in Power BI from end to end. I performed data cleaning and preparation in Power Query, designed a structured data model (fact + dimension tables), created key KPI measures, and developed an interactive dashboard that supports performance monitoring across products/brands, regions, customer demographics, and time.

## Objectives
Clean and prepare the dataset for analysis using Power Query  
Build a reliable data model with proper relationships between tables  
Develop core KPIs to measure business performance  
Create an interactive dashboard to analyze performance by:
Brand
Region
Category
Customer attributes (e.g., income level)
Time (monthly/yearly trends)

## Tools Used
Power BI Desktop
Power Query (data cleaning & transformation)
Data Modeling (relationships)
DAX (measures/KPIs)
Visualizations, filters, and dashboard design

## Data Model
To support accurate filtering and reporting, I built a structured model with:
Sales (Fact Table): transactions (SaleID, SaleDate, Quantity, Unit Price, Unit Cost, ProductID, CustomerID)
Products (Dimension Table): Brand, Category, Color, ProductName, Weight, ProductID
Customers (Dimension Table): CustomerName, Gender, Age, IncomeLevel, Region, SignupDate, CustomerID
This model enables consistent analysis across product and customer dimensions.

## Data Cleaning & Preparation (Power Query)
I used Power Query to ensure data quality and consistency before analysis, including:
Correcting and standardizing data types (dates and numeric fields)
Cleaning text fields (consistent naming for Brand/Region/Category/Color)
Checking for missing values and invalid entries
Validating key columns used for measures (Quantity, Unit Price, Unit Cost)
Ensuring the dataset loads cleanly into the model for accurate visuals and KPIs

## KPIs (Dashboard Level)
The report highlights key performance metrics, including:
Revenue: 3M  
COGS: 2M  
Profit: 932K  
Customers: 250  

## Dashboard Features
The dashboard was designed for quick decision-making and includes:
Profit by Brand (compare brand profitability)
Total Sales by Color (product attribute performance)
Total Sales by Year (high-level time trend)
Total Customers by Month (customer activity trend)
Profit by Income Level (customer segmentation insight)

## Interactivity (Filters/Slicers)
To enable easy exploration, the dashboard includes slicers for:
Brand
Region

## Key Outcomes / What This Project Demonstrates
End-to-end BI workflow: ETL → Modeling → DAX → Dashboard design
Ability to structure datasets into a model that supports scalable reporting
Creation of KPIs that summarize performance clearly for stakeholders
Building interactive visuals that allow users to drill into brand and regional performance

