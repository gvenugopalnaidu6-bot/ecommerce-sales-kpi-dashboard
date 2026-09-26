# ecommerce-sales-kpi-dashboard
# E-Commerce Sales KPI Dashboard | Power BI, SQL & Python

## 📊 Project Overview
End-to-End E-Commerce Sales Analysis Project. 3 Years sales data ni analyze chesi business KPIs track chesanu. Interactive dashboard build chesanu.

**Project Link:** https://github.com/gvenugopalnaidu6-bot/ecommerce-sales-kpi-dashboard
**Tools Used:** Power BI, MySQL, Python (Pandas), Excel

## 🎯 Key KPIs I Calculated
- Total Sales & Total Profit
- Profit Margin % 
- Total Orders & AOV
- YoY Sales Growth
- Top 5 Products by Sales
- Sales by Region, State, Category
- Monthly Sales Trend

## 🛠️ My Process

**Step 1: Data Cleaning (Python & Excel)**
- sales2017_raw.csv file lo null values, duplicates remove chesanu
- Python Pandas tho category names clean chesanu

**Step 2: Data Analysis (SQL)**
- SQL JOINS use chesi tables connect chesanu
- GROUP BY, SUM, AVG queries tho KPIs calculate chesanu

**Step 3: Dashboard (Power BI)**
- Power BI lo slicers (Date, Region) add chesanu
- DAX Measures create chesanu: 
  Total Sales = SUM(Sales)
  Profit Margin = DIVIDE([Total Profit], [Total Sales])
- Bar chart, Line chart, Map, KPI Cards use chesanu

## 📁 Files in this Repo
- POWER BI DASH BOARD CRATION.pbix -> Main Dashboard File
- sales2017_raw.csv -> Raw Data
- sample-data-10mins.xlsx -> Sample Data
- online_store_MSSQL.sql -> My SQL Queries

## 💡 Key Insights
1. West Region lo highest sales vachayi (35%)
2. Technology Category lo highest Profit Margin undi
3. December lo sales ekkuva - Holiday season effect
4. Top 3 products 22% revenue ichayi

## 🚀 How to Run
1. .pbix file ni Power BI Desktop lo open cheyyandi
2. sales2017_raw.csv tho data refresh cheyyandi

---
**Author:** Venu Gopal Naidu E | Aspiring Data Analyst
**Skills:** SQL | Power BI | Python | Excel
**LinkedIn:** [Your LinkedIn Link Add Cheyyi]
