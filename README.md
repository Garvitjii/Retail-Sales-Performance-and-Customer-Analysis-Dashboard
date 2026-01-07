# 🍕 Pizza Sales Data Analysis & Power BI Dashboard
## 📌 Project Overview
- This project analyzes pizza sales data using a single consolidated dataset to extract business insights related to revenue, sales performance, and customer ordering behavior.
- The project follows a complete data analytics workflow:
Data Cleaning → SQL Analysis → Power BI Visualization.
- All KPIs, trends, and insights are derived from one cleaned table containing the full sales data.

---

## 🎯 Project Objectives
- Clean and prepare raw pizza sales data
- Perform KPI calculations using SQL
- Analyze daily, weekly, and monthly sales trends
- Identify top 5 and bottom 5 performing pizzas
- Build an interactive Power BI dashboard for business insights

---

## 🛠 Tech Stack
- SQL (SELECT, GROUP BY, ORDER BY ,CAST , Aggregations)
- SQL Server Management Studio (SSMS)
- Power BI
- CSV Dataset

---

## 🧹 Data Cleaning
- Data cleaning was performed before analysis to ensure accuracy:
- Removed duplicate records
- Handled missing and null values
- Standardized date and time formats
- Verified numeric fields such as quantity and price
- Ensured consistent category and size naming

---

## 📊 KPIs Calculated Using SQL
- The following KPIs were calculated directly from the single table:
- Total Revenue
- Total Orders
- Total Pizzas Sold
- Average Order Value (AOV)
- Average Pizzas per Order

These KPIs are used as headline metrics in the dashboard.

---

## 📈 Sales & Trend Analysis (SQL-Based)
- Time-Based Analysis
- Daily sales trends
- Total Orders Based On Week
- Total Orders Based On Month
- Product-Based Analysis
- Sales by pizza category
- Sales by pizza size
- Top 5 pizzas by revenue
- Bottom 5 pizzas by revenue
- Top 5 pizzas by quantity sold

All calculations and aggregations were performed using SQL queries in SSMS.

---

## 📊 Power BI Dashboard
- After completing SQL analysis, the processed data was imported into Power BI to build an interactive dashboard.

🔹 Dashboard Features
- KPI cards for revenue, orders, and averages
- Bar charts and column charts for trends
- Category and size-based analysis
- Top and bottom pizza performance visuals
- Interactive slicers for dynamic filtering

---

## 💡 Key Business Insights
- Thai Chicken pizza category contributes the highest revenue
- Friday / Saturday Evening hours show peak order volume
- Customers order approximately 2.3 pizzas per order on average
- Medium and Large pizzas are the most popular sizes

---

## 🚀 How to Run This Project
- Load the CSV file into SQL Server Management Studio
- Perform data cleaning and KPI calculations using SQL
- Export the processed data
- Import the data into Power BI
- Explore insights using the interactive dashboard



