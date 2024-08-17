# Retail Sales Analyzer

This Python script provides a simple and effective way to analyze retail sales data using the Pandas and Matplotlib libraries. The script reads sales data from a CSV file, processes it, and provides various insights and visualizations.

## Features

- **Data Cleaning**: The script removes any missing values from the dataset.
- **Total Sales Per Product**: Calculates the total sales for each product.
- **Best Selling Product**: Identifies the best-selling product based on total sales.
- **Average Daily Sales**: Computes the average daily sales across the dataset.
- **Sales Trend Visualization**: Plots the sales trend over time.
- **Sales Per Product Visualization**: Plots the total sales per product in a bar chart.

## Requirements

- Python 3.x
- Pandas
- Matplotlib

You can install the required packages using pip:

```bash
pip install pandas matplotlib
```
## Usage

1. **Data Preparation**: Ensure you have a CSV file named `retail_sales.csv` with the following columns:
   - `Date`: The date of the sales (in YYYY-MM-DD format).
   - `Product`: The name of the product.
   - `Sales`: The sales amount.

2. **Running the Script**: Simply run the script to get the analysis results. The script will print out the total sales per product, the best-selling product, and the average daily sales. It will also display two plots: one for the sales trend over time and another for sales per product.

```python
analyzer = RetailSalesAnalyzer()
print('Total Sales per Product: \n', analyzer.total_sales_per_product())
print('Best Selling Product: ', analyzer.best_selling_product())
print('Average Daily Sales: ', analyzer.average_daily_Sales())
analyzer.plot_sales_per_product()
analyzer.plot_sales_trend()
```
## Outcomes

### Textual Output:
- **Total Sales per Product:** Shows the total sales for each product.
- **Best-Selling Product:** Identifies the product with the highest sales.
- **Average Daily Sales:** Displays the average daily sales across all dates.

### Visual Output:
- **Sales Per Product Bar Chart:** Visualizes the sales distribution among products.
- **Sales Trend Line Chart:** Plots the sales trend over time.

## Conclusion
This script provides a comprehensive way to analyze retail sales data, from cleaning and processing the data to performing key analyses and visualizations. The class-based structure makes

