# Financial Analysis Project

This project is a financial analysis workflow built in a Jupyter notebook. It demonstrates how to clean and transform sales data, compute financial metrics, and visualize performance across products, countries, and time.

## What it does
- Loads financial data from a CSV file
- Cleans currency and numeric columns by removing `$`, commas, and extra characters
- Converts columns such as `Sales`, `COGS`, `Profit`, `Discounts`, `Manufacturing Price`, and `Sale Price` to numeric values
- Fills missing values and computes new metrics like `Profit` and `Discounts`
- Provides summary statistics and exploratory data analysis
- Creates visualizations for product profitability, yearly trends, country/segment performance, and monthly profit

## Files
- `script/financial_analysis.ipynb`: main notebook containing the data cleaning and analysis steps
- `data/`: expected location for CSV data files
- `dashboard/`: dashboard-related files or visualization outputs
- `images/`: saved charts or image exports

## How to use
1. Put the source CSV into `data/` or update the notebook path to your file location.
2. Open `script/financial_analysis.ipynb` in Jupyter or VS Code.
3. Run the notebook cells to clean, analyze, and visualize the financial dataset.

## Goals
- turn raw financial sales data into a clean analysis-ready dataset
- identify profitable products and country performance
- prepare visual insights for financial decision-making

## Requirements
- Python
- pandas
- numpy
- matplotlib
- seaborn
