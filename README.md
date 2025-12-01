# 📊 Data Analytics Portfolio — E-Commerce Projects

This repository contains **two end-to-end e-commerce analytics projects**, showcasing skills in data cleaning, transformation, exploratory data analysis, SQL, visualization, and statistical testing.  
Each project demonstrates analytical thinking and practical business insights.

---

# **Project 1 — E-commerce Sales, Profitability & Customer Behavior Analysis**

This project provides a complete analysis of three CSV datasets (events, products, countries).  
It includes data preparation, feature engineering, revenue analysis, category performance, regional insights, delivery trends, and seasonality.

## Key Objectives
- Analyze sales, profit, and order distribution  
- Evaluate product category performance  
- Identify regional and sales channel patterns  
- Assess delivery time and its effect on profitability  
- Detect seasonal trends across top product categories  

## Data Preparation 
- Cleaned missing values and duplicates  
- Converted date columns to datetime  
- Engineered metrics: **Revenue**, **Cost**, **Profit**, **Delivery Time**  
- Merged datasets via product and country identifiers  

## Main Findings
- Total orders: **1,330**  
- Total revenue: **1.7B USD**  
- Total profit: **501M USD**  
- Best-performing categories: **Cosmetics**, **Household**, **Office Supplies**  
- Lowest categories: **Fruits**, **Beverages**  
- **Europe** is the highest-revenue region  
- **Monday** generates the highest revenue  

---

# **Project 2 — Global E-Commerce Insights with BigQuery & Python**  
*(Advanced EDA, SQL, Statistical Testing, Visualizations)*

This project analyzes global e-commerce data sourced directly from **Google BigQuery**.  
It includes SQL queries, exploratory analysis, segmentation, statistical tests, and advanced visualizations.

## Goals
- Load and query BigQuery data using Python  
- Explore sessions, orders, user behavior, and geographic patterns  
- Analyze product categories and top-performing regions  
- Build time-series sales dynamics and detect seasonal peaks  
- Apply statistical tests:
  - Pearson correlation  
  - Mann-Whitney U test  
  - Proportions Z-test  
- Create pivot tables for deeper comparisons  

## Data Sources
SQL query joins:

- `DA.session`  
- `DA.session_params`  
- `DA.order`  
- `DA.product`  
- `DA.account_session`  
- `DA.account`

## Key Insights

### Geographic Performance
- Top continents by sales: **America, Europe, Asia**  
- Top countries: **USA, India, Germany, Italy, UK**

### Product Categories
- Global leaders: **Sofa & Armchairs**, **Chairs**  
- Unique category differences appear in specific countries  

### User Behavior
- Verified users: **~65–75%**  
- Unsubscribed users: **~15–25%**  
- Registered users purchase more frequently  
- Guest users have a higher average order value  

### Sales Dynamics
- Major seasonal spike in **December**  
- Demand decline in early **February**  
- High cross-continent correlation (**r > 0.8**) indicates synchronized market behavior  

### Pivot Tables
- Unique sessions by **device × traffic channel**  
- Sales of top categories in **top countries**  
- Average order value by **continent × device**

### Statistical Analysis
- **Pearson r:** sessions vs daily sales  
- **Mann-Whitney U:** guest vs registered purchases  
- **Z-test:** comparing organic traffic share in Europe vs America  

---

# Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- SciPy, Statsmodels  
- Google BigQuery  
- Google Colab  

---

# Files Included
- **Project 1 Notebook** — CSV-based analysis  
- **Project 2 Notebook** — SQL + EDA + statistical analysis  
- **final_sales_portfolio.csv** — exported cleaned dataset  
- **Graphs and visual outputs**

---

# Summary
This repository demonstrates strong proficiency in:

- SQL & BigQuery data extraction  
- End-to-end EDA  
- Data cleaning and feature engineering  
- Segmentation and business insights  
- Statistical hypothesis testing  
- Data visualization and storytelling  

Both projects are portfolio-ready and can be further extended with dashboards or predictive modeling.
Data visualization and storytelling

Both projects are ready for portfolio presentation and can be expanded with dashboards or machine learning components.
