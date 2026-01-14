# zepto-sql-product-analysis
Retail product and inventory analysis using SQL.

## Overview
This project focuses on analyzing retail product and inventory data using SQL.
The objective is to uncover pricing, discount, and inventory insights that can
support better business and operational decisions.

## Dataset
- Retail product-level data
- Includes pricing, discounts, stock status, quantity, and weight information

## Tools Used
- SQL (PostgreSQL)
- Relational Database Design
- Data Cleaning & Analysis

## Key Analysis Performed
- Data exploration and validation
- Handling invalid pricing data
- Stock availability analysis
- Discount and pricing analysis
- Revenue estimation by category
- Price-per-gram value analysis
- Inventory weight distribution

## Business Insights
- Identified best-value products based on discount percentage
- Highlighted high-value products that were out of stock
- Ranked categories by revenue and average discount
- Found pricing inefficiencies in premium products
- Supported inventory planning using weight-based categorization

## How to Run
1. Create the table using `zepto_schema.sql`
2. Insert dataset records
3. Run queries from `zepto_analysis.sql` in PostgreSQL
