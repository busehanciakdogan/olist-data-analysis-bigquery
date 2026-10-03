# Olist E-Commerce Data Analysis | BigQuery & SQL

## Project Overview

This project presents an e-commerce data analysis of the Brazilian Olist marketplace using Google BigQuery and SQL.

The analysis focuses on sales performance, customer behavior, product and category performance, payment methods, and revenue trends.

## Tools & Technologies

- Google BigQuery
- SQL
- Data Cleaning
- Data Analysis
- Window Functions

## Datasets

The analysis uses multiple Olist datasets, including:

- Customers
- Orders
- Order Items
- Order Payments
- Order Reviews
- Products
- Sellers
- Geolocation
- Product Category Translation

## Data Preparation

The datasets were prepared for analysis by:

- Checking primary keys and duplicate records
- Investigating NULL values and missing information
- Standardizing date and timestamp fields
- Validating product and order identifiers
- Checking price and freight value data types
- Standardizing product category names
- Combining related datasets using SQL JOIN operations

## Analysis

### Sales & Revenue Analysis

The project examines:

- Total revenue
- Monthly revenue trends
- Average Order Value (AOV)
- Revenue by payment type
- Cancelled orders
- Sales trends over time

### Product & Category Analysis

Product performance was analyzed through:

- Best-selling products
- Highest-revenue products
- Category-level sales
- Average product prices
- Orders per product
- Highest-performing categories

### Customer Analysis

Customers were segmented based on order frequency.

Customer Lifetime Value (CLV) and revenue contribution were also analyzed to understand customer value and purchasing behavior.

### SQL Window Functions

SQL Window Functions were used to perform cumulative revenue analysis and identify revenue trends over time.

## Key Results

- Total revenue: ₺13.59 million
- Total unique orders: 98,666
- Average Order Value (AOV): ₺137.75

The analysis also identified differences in revenue contribution across products, categories, and customer segments.

## Business Recommendations

Based on the analysis:

- Develop targeted campaigns for loyal customers.
- Allocate more marketing budget to high-revenue categories.
- Develop improvement strategies for underperforming categories.
- Monitor monthly sales trends for seasonal planning.

## Project Report

The detailed project analysis and findings are available in the presentation below:

[Olist Data Analysis Report](./Olist-veri-analizi.pptx)

## Project Structure

```text
olist-data-analysis-bigquery/
│
├── Olist-veri-analizi.pptx
└── README.md
