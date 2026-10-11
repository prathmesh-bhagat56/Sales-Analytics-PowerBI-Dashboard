[README.md](https://github.com/user-attachments/files/33307014/README.md)
# Sales Analytics Dashboard - Power BI Project

## Overview
This project analyzes a company's historical sales dataset (7,991 orders from January 2017 to December 2019 across 50 customers, 100 delivery regions, and 15 products) to track revenue, profitability, customer performance, warehouse fulfillment times, and regional demand.

## Problem Statement
The business needed a consolidated view of orders, shipping timelines, customer accounts, and product margins to identify high-performing channels, manage currency exposure, and improve warehouse processing times.

## Project Objectives Covered
1. **Overview Metrics**: Total Sales ($154.57M), Total COGS ($96.78M), Gross Profit ($57.79M), Profit Margin (37.39%), and Average Unit Price ($2,284.54).
2. **Sales Trends**: Monthly and yearly revenue trends from 2017 to 2019, highlighting peak sales in 2018 ($53.46M) and seasonal highs in March and Q3.
3. **Customer Insights**: Order volume and total revenue by customer, led by Medline ($4.08M, 210 orders), Pure Group ($3.82M), and OUR Ltd ($3.68M).
4. **Channel Analysis**: Performance breakdown across Wholesale (53.67% of sales), Distributor (31.68%), and Export (14.64%).
5. **Currency Impact**: Sales distribution across NZD (37.62%), USD (28.89%), AUD (16.76%), EUR (8.50%), and GBP (8.24%).
6. **Warehouse Efficiency**: Order processing and shipping time analysis across 6 warehouses (overall average fulfillment time of 10.44 days; fastest average at FLR025 with 10.05 days).
7. **Product Performance**: Revenue and quantity breakdown by product. Top 7 products account for 85.87% of total revenue, led by Product 7 ($25.71M) and Product 1 ($25.49M).
8. **Cost and Profitability**: Unit price vs. unit cost and profit margin comparison across products (Product 14 has the highest margin at 40.15%).
9. **Regional Analysis**: Sales distribution across New Zealand delivery cities, led by Christchurch ($11.53M), Hamilton ($11.49M), and Waitakere ($11.19M).

## Files in This Repository
- `Sales_Analytics_Dashboard.pbix` - Main Power BI Desktop dashboard file (3 report pages: Executive & Trends, Customers & Products, Logistics & Regions).
- `Sales_Analytics_Dashboard.pbip` - Power BI Project file for version control.
- `dax_measures.dax` - DAX measures used in the report.
- `powerbi_theme.json` - Custom color theme file used in Power BI Desktop.
- `data/sales_dataset.xlsx` - Original dataset containing Sales Orders, Customers, Regions, and Products sheets.
- `data/clean_tables/` - Cleaned CSV tables used for the Star Schema model (`Fact_Sales_Orders.csv`, `Dim_Customers.csv`, `Dim_Products.csv`, `Dim_Regions.csv`).
- `index.html`, `styles.css`, `app.js` - Web version of the dashboard for browser viewing.

## How to Open
1. Download `Sales_Analytics_Dashboard.pbix` and open it in **Microsoft Power BI Desktop**.
2. To view the web version in a browser, open `index.html`.
