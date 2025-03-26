# AtilQ-Business-Intelligence--MySQL
SQL procedures and views for financial and supply chain analytics, including customer sales reports, forecast accuracy analysis, and top N products/customers/markets by net sales. The scripts help generate insights for data-driven decision-making in retail and supply chain management.
# SQL Procedures and Views for Financial & Supply Chain Analytics

This repository contains SQL scripts for generating reports and insights in financial and supply chain analytics, including:

- **Customer-wise sales reports**
- **Forecast accuracy analysis**
- **Top N products, customers, and markets by net sales**

## Overview

The SQL procedures and views help generate detailed insights for data-driven decision-making in retail and supply chain management. These scripts are designed to aggregate and analyze data from different tables, providing actionable insights for business operations.

## Table of Contents

1. [Stored Procedures](#stored-procedures)
2. [Views](#views)
3. [Usage](#usage)
4. [Contributing](#contributing)

## Stored Procedures

1. **`get_customer_wise_sale_report`**:  
   Retrieves customer-wise sales reports by fiscal year, market, and customer code.

2. **`get_forecast_accuracy`**:  
   Analyzes forecast accuracy by calculating forecast errors and percentages.

3. **`get_top_n_customers_by_net_sales`**:  
   Fetches the top N customers by net sales for a given fiscal year and market.

4. **`get_top_n_market_by_net_sales`**:  
   Retrieves the top N markets by net sales for a given fiscal year.

5. **`get_top_n_products_by_net_sales`**:  
   Fetches the top N products by net sales for a given fiscal year.

6. **`get_top_n_products_per_division_by_qty_sold`**:  
   Retrieves the top N products by quantity sold per division.

## Views

1. **`gross_sales`**:  
   A view that combines sales data, product information, and gross price to calculate total gross sales.

2. **`net_sales`**:  
   A view that computes net sales by applying post-invoice discounts.

3. **`sales_postinv_discount`**:  
   A view that calculates net invoice sales after pre- and post-invoice discounts.

4. **`sales_preinv_discount`**:  
   A view that calculates sales data before any invoice discounts are applied.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Akshay6249/AtilQ-Business-Intelligence--MySQL/commits?author=Akshay6249
