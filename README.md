# E-commerce Sales, Profitability, and Customer Behavior Analysis

This project presents an end-to-end analysis of e-commerce data, including sales performance, profitability, delivery efficiency, seasonality, category performance, and regional trends.  
The analysis combines three datasets (events, products, countries) and applies Python-based data processing, feature engineering, and visualization.

---

## Key Objectives
- Evaluate sales, profit, and order distribution.
- Analyse product category performance.
- Identify patterns across regions, sales channels, and weekdays.
- Assess delivery time and its influence on profitability.
- Detect seasonal trends for top product categories.

---

## Data Preparation
- Loaded three datasets: `events.csv`, `products.csv`, `countries.csv`.
- Handled missing values and duplicates.
- Converted date fields to datetime format.
- Engineered new metrics: Revenue, Cost, Profit, Delivery Time.
- Merged datasets using product and country identifiers.

---

## Analytical Components

### 1. Overall Business Metrics
- Total orders: 1,330  
- Total revenue: 1,702,129,408.21 USD  
- Total profit: 501,434,459.0 USD  
- Countries included in the dataset: 45  

### 2. Revenue Dynamics
Revenue over time shows irregular fluctuations with peak sales in certain periods.  
Despite temporary declines, overall revenue remains stable without a downward trend.

### 3. Category Performance
- Highest revenue categories: Cosmetics, Household, Office Supplies  
- Lowest: Fruits and Beverages  
- Average profit varies significantly across product groups.

### 4. Regional Insights
- Europe generates the highest sales volume.  
- Asia has the lowest sales among the analysed markets.

### 5. Sales Channels
Analysis compares online and offline revenue distribution using pie and bar charts.

### 6. Delivery Time Analysis
- Average delivery time ranges between 21–27 days.
- Delivery delay impacts profitability and customer experience.

### 7. Weekday Revenue Patterns
- Monday shows the highest revenue.
- Tuesday records the lowest.

### 8. Seasonality
Top 5 product categories exhibit clear month-to-month trends:
- Office Supplies and Household peak in spring and summer.
- Cosmetics and Meat increase toward the end of the year.

---

## Technologies & Tools
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  
- CSV datasets (events, products, countries)

---

## Files Included
- **Colab Notebook:** Full analysis workflow  
- **Plots:** Revenue, delivery time, profitability, seasonality, regional trends  
- **Merged dataset preview**

---

## Summary
This project demonstrates analytical capabilities in:
- data preparation, cleaning, and transformation  
- building derived metrics (Revenue, Profit, Delivery Time)  
- visual analytics and pattern identification  
- business insights extraction  
- e-commerce performance evaluation  

It can serve as a foundation for more advanced modelling, forecasting, or dashboarding.

