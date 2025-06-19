# Sales-SQL-Analysis
Dataset: https://www.kaggle.com/datasets/abdullah0a/retail-sales-data-with-seasonal-trends-and-marketing/data
# Overview
This project showcases SQL and data analysis skills using a retail sales dataset containing transactional data for a subset of months in 2020. The goal is to simulate real-world business analysis by performing data cleaning, writing analytical SQL queries, and creating visualizations in Jupyter Notebook using SQLite.

# How to Run
Clone the repository
Install requirements:
pip install pandas matplotlib seaborn sqlalchemy ipython-sql
Open the Jupyter Notebook

Run all cells to recreate the analysis and visuals

# Dataset Summary
The dataset contains ~30,000 records and includes the following columns:
Column	Description
year, month	Time indicators
supplier	Product supplier (nullable)
item_code	Unique product ID
item_description	Product name
item_type	Product category
retail_sales	Revenue from retail sales
retail_transfers	Inventory transfers to retail stores
warehouse_sales	Sales made from warehouses

Note: The dataset covers only January, March, July, and September 2020.

# Data Cleaning
Filled missing supplier names with 'Unknown'
Removed or handled missing sales values
Standardized inconsistent formatting in categorical columns

# Key Business Questions Answered
Top-performing product categories
Months where retail sales underperformed vs transfers (Red Flags)
Green vs Yellow vs Red classification
Top item types using a CTE + window function
Average Monthly Sales Per Item Type
and more...

# Visualizations
Bar chart of average monthly sales by item type
Ranking of top 3 item types per year
Monthly retail sales bars colored by performance flags
All visuals created in Jupyter Notebook using matplotlib and seaborn

# Outcome
Despite limited monthly data, this project effectively simulates the workflow of a business/data analyst : 
including data wrangling, metric computation, trend detection, and result communication using SQL and Python.
