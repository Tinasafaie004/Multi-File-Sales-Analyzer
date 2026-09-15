# Multi-File Sales Analyzer

This project combines data from multiple CSV files for an online electronics retailer. The workflow follows the assignment scenario: inspect raw files, clean datasets, merge customer and product information into order records, create business metrics, investigate unmatched records, and export the final analysis-ready dataset.

## Files

- `customers.csv`
- `products.csv`
- `january_orders.csv`
- `february_orders.csv`
- `march_orders.csv`
- `sales_analyzer.py`
- `sales_analysis.csv`

## Project Goal

Create a single cleaned, merged dataset named `sales_data` by combining orders with customer and product reference files. Then produce business questions such as high-value orders, Gold customer activity, Toronto Electronics orders, inventory attention products, and top orders.

## Output

The program writes the final merged and cleaned dataset to `sales_analysis.csv` without the Pandas index.
