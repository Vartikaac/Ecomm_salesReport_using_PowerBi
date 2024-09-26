# ECOMM Sales Report - Power BI Project

## Project Overview

This **ECOMM Sales Report** is designed to analyze sales, profit, shipping costs, and other key business metrics to help companies make data-driven decisions. The dashboard offers insights into top sales by country, state, market, and category, enabling companies to evaluate their performance in various regions and segments. This report also tracks the efficiency of different shipping modes to optimize logistics costs.

The goal of this dashboard is to assist decision-makers in identifying high-performing regions, product categories, and shipping methods, while providing a clear visual representation of business performance across multiple dimensions.

---

## Problem Statement

In a rapidly growing e-commerce environment, companies often struggle to track their performance across various markets and categories. Understanding sales patterns by country, state, product category, and shipping mode is essential for making informed decisions and improving profitability. Without a clear understanding of these patterns, companies may miss opportunities for optimization and growth.

This dashboard solves the problem by providing detailed visualizations of:
- Total sales, profit, and shipping costs
- Top 5 sales by country and state
- Sales trends across different markets and shipping modes

---

## Key Metrics

1. **Total Sales**: Measures the overall revenue generated from all products.
2. **Profit**: Highlights the earnings after deducting costs.
3. **Shipping Costs**: Provides insights into logistics expenses.
4. **Orders**: Tracks the total number of orders placed.
5. **Quantity Sold**: Shows the total number of units sold.

---
## View Project: Ecomm Sales Performance Analysis

![Ecomm Sales Performance Analysis Dashboard](ECOMM%20SALES%20REPORT/ecom%20chart.png)

---

## Dashboard Components

### 1. **Total Sales, Profit, and Shipping Costs**
   - Displays the cumulative sales, profit, and shipping costs across all products.
   - Helps in understanding the overall financial health of the business.

### 2. **Top 5 Sales by Country**
   - A donut chart visualizing the top 5 countries contributing to the highest sales.
   - Enables easy identification of high-performing regions.

### 3. **Top 5 Sales by State**
   - A treemap showing the top-performing states in terms of sales.
   - Helps in regional analysis and identifying geographical trends.

### 4. **Sum of Sales by Category**
   - Bar chart representing sales distribution across product categories like Technology, Furniture, and Office Supplies.
   - Assists in identifying the best-performing categories.

### 5. **Sum of Sales by Market**
   - A pie chart showing the distribution of sales across different markets (e.g., APAC, EMEA, US, etc.).
   - Provides insights into market penetration and performance.

### 6. **Sum of Sales by Ship Mode**
   - A bar chart illustrating the efficiency of different shipping modes (Standard Class, Second Class, First Class, Same Day).
   - Helps in optimizing shipping strategies by understanding which methods are the most cost-effective.

---

## Dataset Details

The project uses **ECOMM DATA.xlsx**, a dataset containing historical sales data, including:
- **Order ID**: Unique identifier for each order
- **Order Date**: Date the order was placed
- **Ship Mode**: Method of shipping (Standard, First Class, etc.)
- **Customer ID**: Identifier for each customer
- **Product Category & Sub-category**: Grouping of products sold
- **Sales, Profit, Quantity**: Sales amount, profit margins, and number of units sold
- **Region, Country, State**: Geographical information for sales tracking

---

## Tools and Technologies Used

1. **Microsoft Power BI**: Used to create interactive dashboards and visualize sales, profits, and other business metrics.
2. **DAX (Data Analysis Expressions)**: Utilized for advanced calculations and data analysis.
3. **Excel**: The data source was prepared and cleaned in Excel before importing into Power BI.

---

## Steps Followed

1. **Data Collection**: The data was sourced from internal e-commerce sales records and prepared in an Excel sheet (ECOMM DATA.xlsx).
   
2. **Data Cleaning**: The dataset was cleaned to remove any inconsistencies, and columns like sales, profit, and shipping costs were reviewed for accuracy.

3. **Data Import to Power BI**: The cleaned dataset was imported into Power BI, and relationships were established between tables for enhanced analysis.

4. **Dashboard Creation**:
    - Created various charts (bar, pie, treemap) to visualize sales performance by category, country, and shipping method.
    - Added slicers and filters to allow dynamic interaction with the data (e.g., filtering by region or shipping mode).
    
5. **Final Presentation**: The final report provides decision-makers with key insights, enabling them to take informed actions to optimize business performance.

---

## Key Insights

- **Top-performing Region**: The highest sales were recorded in the **US** (42.46%), followed by **Germany** (17.1%).
- **Profitable Product Category**: The **Technology** category contributed the most to sales, followed closely by **Furniture** and **Office Supplies**.
- **Efficient Shipping Mode**: **Standard Class** shipping accounted for the highest number of orders, but **First Class** provided better profit margins.
  
---

## How to Use

1. **Download the Project Files**: Clone the repository to your local machine.
   ```bash
   git clone https://github.com/your-repo/data-analytic-project-with-power-bi.git
