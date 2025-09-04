# 📊 Business Data Analytics Project  

This repository contains a collection of **SQL scripts** and **data views** for a business data analytics project.  
The project focuses on **exploring and analyzing key business data** to derive insights related to **customers, products, and overall performance**.  

---

## 🚀 Project Overview  

The project is structured into three main areas of analysis:  

1. **Exploratory Data Analysis (EDA)**  
   - Understand the structure, content, and key metrics of the database.  

2. **Advanced Analytics**  
   - Perform in-depth analysis including **trend, performance, and segmentation analysis**.  

3. **Reporting**  
   - Build consolidated **SQL views** for customer and product performance reporting.  

---

## 📂 Files  

### 1. `SQL Exploratory Data Analysis (EDA).sql`  
Contains foundational SQL queries for exploring the database.  

- **Database Exploration**  
  - List all objects and columns within the `gold` schema.  

- **Dimensions Exploration**  
  - Identify unique values in dimension tables (`dim_customers`, `dim_products`).  
  - Example: countries in `dim_customers`, categories in `dim_products`.  

- **Data Exploration**  
  - Find earliest and latest dates in `fact_orders`.  
  - Understand customer age ranges.  

- **Measures Exploration**  
  - High-level aggregation queries (e.g., total sales, items sold, total orders).  

- **Magnitude Analysis**  
  - Compare measures by categories (e.g., total customers by country, revenue by product category).  

- **Ranking Analysis**  
  - Rank dimensions by measure values.  
  - Example: Top 5 products by revenue, Top 3 customers by orders.  

---

### 2. `Advanced_Analytics.sql`  
More complex SQL queries for advanced business analysis.  

- **Changes Over Time Analysis**  
  - Track key metrics (sales, customers) monthly to identify trends.  

- **Cumulative Analysis**  
  - Running totals and moving averages for business growth or decline.  

- **Performance Analysis**  
  - Compare current sales to averages or prior year performance.  

- **Part-to-Whole Analysis**  
  - Understand contributions of categories (e.g., which category drives most revenue).  

- **Data Segmentation**  
  - Group data into categories for insights.  
  - Example: Segment customers into *VIP*, *Regular*, *New* based on spending and lifespan.  

---

### 3. `report_customers_view.sql`  
Creates a consolidated SQL view: **`gold.report_customers`**.  

- **Key Fields**  
  - Names, ages, transaction details.  

- **Customer Segmentation**  
  - Categories: *VIP*, *Regular*, *New*.  
  - Age groups: *Under 20*, *20-29*, etc.  

- **Key Performance Indicators (KPIs)**  
  - Total orders, total sales, total quantity purchased, total products, lifespan.  
  - Calculated metrics: *Recency*, *Average Order Value (AOV)*, *Average Monthly Spend*.  

---

### 4. `report_products_view.sql`  
Creates a consolidated SQL view: **`gold.report_products`**.  

- **Key Fields**  
  - Product name, category, subcategory, cost.  

- **Product Segmentation**  
  - Categories: *High-Performers*, *Mid-Range*, *Low-Performers*.  

- **Key Performance Indicators (KPIs)**  
  - Total orders, total sales, total quantity sold, total customers.  
  - Calculated metrics: *Recency*, *Average Order Revenue*, *Average Monthly Revenue*.  

---

## 📈 Key Outcomes  

- Structured approach to **exploring and analyzing data**.  
- SQL scripts that support **business insights** at customer and product levels.  
- Consolidated **views for reporting** in BI tools (Power BI, Tableau, etc.).  

---
