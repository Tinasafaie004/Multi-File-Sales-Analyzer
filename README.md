# Multi-File Sales Analyzer

This project combines data from multiple CSV files for an online electronics retailer. It inspects the raw files, cleans the datasets, merges customer and product information into order records, creates business metrics, investigates unmatched records, and exports a final analysis-ready dataset.

## Files

- `customers.csv`
- `products.csv`
- `january_orders.csv`
- `february_orders.csv`
- `march_orders.csv`
- `sales_analyzer.py`

## Project Goal

Create a single cleaned, merged dataset named `sales_data` by combining orders with customer and product reference files. Then use it to answer business questions about high-value orders, Gold customer activity, Toronto Electronics orders, products needing inventory attention, and top orders.

## Run the project

Install Pandas, then run the script from this folder:

```bash
pip install pandas
python sales_analyzer.py
```

## Output

The program writes the final merged and cleaned dataset to `sales_analysis.csv` without the Pandas index.
