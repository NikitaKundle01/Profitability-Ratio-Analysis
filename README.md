# Profitability Ratio Analysis of Companies

## Project Overview

This project focuses on analyzing the profitability ratios of different companies or products. The goal is to calculate key profitability metrics such as **Gross Margin**, **Net Margin**, **Operating Margin**, **Return on Equity (ROE)**, and **Return on Assets (ROA)**. These metrics help evaluate the financial health and operational efficiency of a company or product. The project also includes trend analysis over time and industry benchmarking.

### Key Concepts:
- **Gross Margin**: Measures how much profit a company makes after covering the cost of goods sold.
- **Net Margin**: Indicates the percentage of revenue that translates into profit after all expenses.
- **Operating Margin**: Shows the percentage of profit a company makes from its core business operations.
- **Return on Equity (ROE)**: Measures the profitability relative to shareholders' equity.
- **Return on Assets (ROA)**: Reflects the ability of a company to generate profit from its total assets.

## Features

1. **Profitability Ratio Calculation**: Calculates key profitability ratios for each product/company.
2. **Industry Benchmarking**: Compares the profitability ratios of different products and provides industry benchmarks.
3. **Trend Analysis**: Visualizes profitability trends over time.
4. **Data Visualization**: Plots various profitability ratios for comparison across products or over time.

## Data Structure

The dataset used in this project should have the following columns:
- `product_code`: Unique identifier for each product.
- `customer_code`: Unique identifier for each customer.
- `market_code`: Unique identifier for each market.
- `order_date`: The date the order was placed.
- `sales_qty`: Quantity of products sold.
- `sales_amount`: Total sales amount.
- `cost_price`: Cost price of the products.
- `profit`: Profit made from the sales.
- `profit_margin`: Profit margin percentage.
- `Revenue`: Total revenue from the sales.
- `Total Expense (COGS)`: Total cost of goods sold.
- `Net Income`: Net income for the company.
- `Total Equity`: Total equity of the company.
- `Total Assets`: Total assets of the company.
- `Operating Income`: Operating income for the company.
- `Gross Margin`: Gross margin percentage.
- `Net Margin`: Net margin percentage.
- `Ratio of Equity`: Ratio of equity to assets.
- `Ratio of Assets`: Ratio of assets to revenue.
- `Operating Margin`: Operating margin percentage.

## Prerequisites

Before running the code, ensure you have the following Python libraries installed:

```bash
pip install pandas matplotlib seaborn
