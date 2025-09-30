# Online Retail Data Analysis

## Overview
Analysis of online retail transaction data to derive business insights and customer behavior patterns.

## Data Processing Steps
1. **Data Loading and Cleaning**
   - Loaded Online Retail dataset with proper encoding
   - Cleaned column names and handled missing values
   - Created derived features (Sales, is_return)
   - Converted data types (CustomerID, InvoiceDate)

2. **Exploratory Data Analysis**
   - Basic statistics for Quantity, UnitPrice, and Sales
   - Customer sales distribution analysis
   - Top 20 products by sales
   - Monthly sales trends
   - Sales heatmap by month and year

3. **Customer Analysis**
   - Top 10 customers by sales volume
   - Monthly seasonality patterns
   - Customer retention through cohort analysis
   - Correlation analysis between key metrics

4. **Visualizations**
   - Histograms of sales distribution
   - Bar charts for product performance
   - Time series analysis of sales
   - Heatmaps for seasonal patterns
   - WordCloud of product descriptions

## Key Insights
- Sales trends over time
- Customer retention patterns
- Top performing products
- Seasonal sales patterns
- Customer purchase behavior

## Output
- Generated clean dataset: `clean_retail_data.csv`
- Various visualizations and statistical analyses

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- WordCloud

## Dataset
Source: Online Retail dataset containing transactions between 2010-2011
