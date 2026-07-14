# Python Sales Analysis

## Project Overview

This project analyzes a retail sales dataset to identify trends, evaluate regional performance, determine the best-selling products, and examine monthly sales patterns. The objective is to transform raw sales data into meaningful business insights that can support strategic decision-making.

## Business Problem

Retail companies generate large amounts of sales data every day. Without proper analysis, it is difficult to identify high-performing regions, best-selling products, and seasonal sales trends.

This project demonstrates how Python can be used to clean, analyze, and visualize sales data to answer key business questions.


## Dataset

The dataset contains retail sales transactions with information such as:

- Order Date
- Ship Date
- Region
- Product Name
- Category
- Sales
- Customer Information


## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook


## Data Cleaning

The following data preparation steps were performed:

- Checked for missing values
- Converted date columns into datetime format
- Verified data types
- Prepared the dataset for analysis


## Business Questions Answered

### 1. Which region generated the highest sales?

A sales-by-region analysis was performed to compare revenue across different geographical regions.

**Insight:**

The analysis identified the highest-performing region, helping management understand where sales efforts are most successful.


### 2. Which products generated the highest sales?

The top 10 products were identified based on total sales.

**Insight:**

Knowing the highest-selling products helps management prioritize inventory planning, promotions, and product availability.


### 3. How do sales vary by month?

Monthly sales were analyzed to identify seasonal patterns.

**Insight:**

The results highlight months with stronger sales performance, allowing businesses to better plan inventory levels and marketing campaigns.


## Key Findings

- Regional sales performance varies significantly.
- A small number of products contribute a large proportion of total sales.
- Sales fluctuate throughout the year, indicating seasonal demand.


## Recommendations

Based on the analysis, the following recommendations are made:

- Increase marketing efforts in lower-performing regions.
- Maintain adequate inventory for high-selling products.
- Prepare promotional campaigns ahead of high-sales months.
- Continue monitoring monthly sales trends to improve forecasting.


## Project Structure

python-sales-analysis/
│
├── data/
│     train.csv
│
├── notebooks/
│     Python Sales Analysis.ipynb
│
├── images/
│     monthly_sales.png
│     sales_by_region.png
│     top_10_products.png
│
└── README.md


## Project Files

- Python Sales Analysis.ipynb
- train.csv
- sales_by_region chart
- top_10_products chart
- monthly_sales chart
