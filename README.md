# Retail Sales Intelligence Using Pandas

## About the Project
This project uses Python and Pandas to combine customer and sales datasets, analyze business performance, and generate sales reports.

## Features
- Load customer and sales CSV files.
- Merge datasets using `CustomerID`.
- Calculate total revenue, sales count, unique customers, and average sale.
- Analyze revenue by city, category, and product.
- Rank cities and products by revenue.
- Export summary reports to CSV files.

## Technologies Used
- Python
- Pandas
- CSV

## Files
- `customers.csv` – Customer details
- `sales.csv` – Sales records
- `retail_sales_analyzer.py` – Main Python script
- `merged_sales_data.csv` – Combined dataset
- `city_summary.csv` – City-wise report
- `category_summary.csv` – Category-wise report
- `product_summary.csv` – Product-wise report

## How to Run
1. Install Pandas: `pip install pandas`
2. Keep the input CSV files and Python script in the same folder.
3. Run the program:

   ```bash
   python retail_sales_analyzer.py
   ```

4. The summary reports will be generated automatically.

## Concepts Used
- Data merging using `merge()`
- Grouping and aggregation using `groupby()` and `agg()`
- Sorting using `sort_values()`
- Exporting data using `to_csv()`
