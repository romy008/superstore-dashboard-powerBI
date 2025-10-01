# 📊 Superstore Sales Dashboard (Power BI)

## 📌 Overview
This project is a **Power BI dashboard** built on the Sample Superstore dataset.  
The goal is to identify which products, regions, categories, and customer segments are most profitable and which should be reconsidered.

---

## 📄 Dataset
- **Source**: Sample Superstore dataset  
- **Period**: 2014 – 2017  
- **Fields**: Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country, City, State, Postal Code, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit  
- **Link**: [Superstore Dataset on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

---

## 📄 Custom Columns & Measures
### Added Columns
- **Profit Margin**: `[Profit] / [Sales]`
- **Order/Ship Date (Year, Month, Date)**: Split [Order Date] and [Ship Date] into [Year], [Month], [Date]

### Key Measures
- **Total Sales**  
- **Total Profit**  
- **Profit Margin (%)**  
- **YoY Sales Growth**

---

## 🧠 Techniques
- **Data cleaning**: Power Query  
- **Visualizations**: Line chart, Bar chart, Donut chart, Table, Map, KPI Cards  
- **Slicers**: allow users to filter by Time, Region, and Category  
- **Drill-down** by Year/Quarter/Month  

---

## ✅ Key Insights
- **Total Sales**: $2.30M across 2014–2017, with +20.34% YoY growth in 2017 vs 2016  
- **Sales Seasonality**: Sales consistently peak in Q4, highlighting strong seasonal demand  
- **West Region**: leading region with the highest sales contribution (~32%) and strong profit performance  
- **Technology**: top-performing category (36% of sales, 17.4% profit margin)  
- **Furniture**: lowest margin (2.49%) → opportunity for supplier negotiation or product mix optimization  

---

## 🛠 Tools
- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Power Query (data transformation & cleaning)  

---

⭐ This project is part of my learning journey in data analytics with Power BI and demonstrates my ability to transform raw data into actionable business insights.
