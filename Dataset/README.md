# 📊 Dataset Information

This folder contains the dataset used for building the GlobalMart India Power BI dashboard.

## 📁 Files Included
- **India_Sales_Dataset.csv** – Cleaned sales dataset used for analysis
- **PowerBI/** – Folder containing Power BI-specific data files 

## 🧾 Dataset Description
- **Time Period:** 2022 – 2024  
- **Geography:** India  
- **Granularity:** Order-level (one row per order line)

## 📌 Key Columns
- Order Date  
- Customer Name  
- Region / State  
- Product Category & Sub-Category  
- Sales  
- Profit  
- Discount  
- Quantity

## 🧮 Derived / Calculated Columns

The following columns and measures were created during data preparation and modelling using **Power Query** and **DAX**.  
This is a representative list and not an exhaustive one.

### 📅 Date Intelligence
- Year
- Month
- Month Name
- Quarter
- Year-Month

### 📊 Performance & Profitability
- Profit Margin (%)
- Discount Amount
- Loss Due to Discount
- Sales per Order

### 👥 Customer & Product Indicators
- Customer Profitability Flag (Profit / Loss-Making)
- Product Profitability Indicator

### 📈 Growth & Trend Metrics
- Year-over-Year (YoY) Growth %
- Running Total (Sales & Profit)

> These derived fields enable advanced time-series analysis, profitability tracking, and trend-based insights.

## 🧩 Data Modelling Approach

- A star schema was implemented in Power BI
- One central fact table for sales transactions
- Dimension tables for Date, Product, Customer, and Region
- One-to-many, single-direction relationships to ensure optimal performance

## 🔗 Dataset Usage

This dataset is used as the primary data source for:
- Executive Overview Dashboard
- Regional & State Performance Analysis
- Product Category Profitability
- Customer-Level Analysis
- Time Series & Trend Analysis

## ⚠️ Notes
- The dataset has been cleaned and transformed using Power Query.
- This data is intended for learning and portfolio demonstration purposes only.
