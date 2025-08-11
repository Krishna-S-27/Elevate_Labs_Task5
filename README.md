## Sales Data Analysis – Task 5
---


## Objective
Analyze sales transaction data to uncover insights such as top-performing regions, best-selling product categories, and sales trends.
This project uses Python, Pandas, and Matplotlib to process and visualize the data.

---

## Dataset Overview
File Name: sales_data.csv , it is a publically avaliable dataset in kaagle.

Link of Dataset: https://www.kaggle.com/datasets/vinothkannaece/sales-dataset?resource=download

Total Orders: 1000.

Total Revenue: ₹ 5,019,265.23.

Regions Covered: North, West, South, East.

Product Categories: Furniture, Food, Clothing, Electronics.

Top Sales Representative: David with ₹ 1,141,737.36 in sales.

---

## Dataset Columns
Column Name	Description
Order_ID	Unique identifier for each sales order.
Region	The geographical region where the sale was made.
Product_Category	Category of the product sold.
Product_Name	Specific product that was sold.
Sales_Rep	Name of the sales representative.
Sale_Date	Date when the transaction occurred.
Sales_Amount	Revenue generated from the sale.

---

## Workflow

1. Load the Dataset
import pandas as pd
df = pd.read_csv("sales_data.csv")

2. Data Cleaning
Converted Sale_Date to datetime format.

Checked for missing or invalid values.

3. Analysis Performed
Total Sales by Region

Sales by Product Category

Top Sales Representatives

Monthly Sales Trends

4. Visualization
Bar Charts → Region-wise and Category-wise sales

Line Chart → Monthly trends

---

## Key Insights
Strongest Region: Determined by total revenue by region.

Best-Selling Category: Found by summing sales by category.

Top Sales Rep: David, contributing over ₹1.14M in revenue.

Seasonal Trends: Noticed peak sales in certain months.

---

## How to Run the Analysis
Install dependencies:
pip install pandas matplotlib
Place sales_data.csv in your working directory.

Run the Python script or Jupyter Notebook:
python sales_analysis.py

View the Charts: Graphs will be displayed for visual insights.

---
