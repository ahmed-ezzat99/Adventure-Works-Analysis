# AdventureWorks Power BI Project (DirectQuery)

## Project Overview
This project is a Power BI report built using the AdventureWorks database and connected to SQL Server through DirectQuery.  
The purpose of this project is to demonstrate practical skills in data modeling, DAX calculations, and building business-oriented dashboards using Power BI.

The report focuses on analyzing sales performance, taxes, freight costs, products, and regional distribution to support business decision-making.

---

## Tools and Technologies
- Power BI
- SQL Server
- DirectQuery
- DAX
- Relational Data Modeling

---

## Data Source
- Database: AdventureWorks
- Connection Mode: DirectQuery
- The data model and tables were already available in the source database.

---

## Data Model
- Fact Table: Sales
- Dimension Tables:
  - Product
  - Dates
  - Territory
  - Customer
  - Ship Method
  - Status

The model follows a star schema design with one-to-many relationships between dimension tables and the fact table.  
Single-direction relationships were used to maintain clarity and performance, which is especially important when working with DirectQuery.

---

## Key KPIs and Metrics
- Total Sales (Subtotal)
- Total Tax
- Total Freight
- Last Year Sales
- Year-over-Year (YoY) Growth
- Order Quantity by Country
- Sales by Category and Region

---

## Dashboard Features
- Sales distribution by region and product category
- Yearly sales trend analysis
- Comparison between current year sales and last year sales
- Freight cost analysis for online and offline orders
- Top products based on sales performance and YoY growth

---

## DAX Measures
The report includes several DAX measures to support business analysis, such as:
- Subtotal
- Total Tax
- Total Freight
- Last Year Sales
- Running Total
- YoY Percentage

Time intelligence functions were used to enable year-over-year comparisons and trend analysis.

---

## Assumptions and Limitations
- ETL steps are not included, as the dataset was already modeled and available through the database.
- Performance depends on the SQL Server source due to the use of DirectQuery.
- Data accuracy relies on the source system.

---

## Project Objective
This project was created as part of a Power BI portfolio to showcase skills in:
- Data modeling
- Writing DAX measures
- Building clear and informative dashboards
- Working with DirectQuery models
