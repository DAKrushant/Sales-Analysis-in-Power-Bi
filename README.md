# 📊 Sales & Profit Analytics Dashboard

### Loan Management – Sales Analysis Project (Excel → Power BI ETL Workflow)
### By: Krushant Shah

### 📁 Project Overview

This project analyzes sales performance for a loan-management assignment using Excel datasets and Power BI.
The entire data pipeline—including data cleaning, transformation, modeling, DAX measures, and dashboard creation—was completed inside Power Query Editor and Power BI Desktop.

### The final dashboard delivers insights on:

  - Total sales & profitability
  - Product-wise performance
  - Customer contribution
  - Category trends
  - Time-series sales analysis

### 📂 Dataset Information

This project uses three Excel/CSV datasets:

  - Sales – Transaction-level information
  - Product – Product category & pricing metadata
  - Customers – Customer master data

### 🔧 Tech Stack Used
#### Phase	Tools Used
  - Data Cleaning	Power Query Editor
  - Transformation	Power Query M Functions
  - Data Modeling	Power BI Model View
  - KPIs & DAX	Power BI Measures
  - Visualization	Power BI Desktop

### 🧹 ETL Process (Excel → Power BI → Dashboard)

### Sales Analysis Notes
### 1️⃣ Data Loading

- All 3 datasets were imported directly from Excel into Power BI.
- While loading, the Customer table header appeared incorrectly (Column1, Column2, ...).

### 2️⃣ Data Cleaning in Power Query Editor

   - Applied "Use First Row as Header" to fix column names.
   - Verified no missing/null values across all datasets.
   - Confirmed correct data types (date, text, whole number, decimal).
   - Renamed columns for clarity where required.
   - Ensured category and product fields were clean and consistent.

### 3️⃣ Data Modeling
#### Created relationships:

Sales[ProductID]  → Product[ProductID]
Sales[CustomerID] → Customers[CustomerID]

A dedicated Measures Table was created to store all DAX measures neatly.

### 📌 DAX Measures Used (KPIs)

  - Total Sales
  - Total Profit
  - Total Quantity
  - Average Selling Price

### 🎛 Filters (Slicers) in Dashboard

  - Sales Date
  - Product Name
  - Customer Name

### 📈 Visuals Included in Dashboard

  - Sales Trend Over Time (Line Chart)
  - Total Sales by Product (Bar Chart)
  - Profit Analysis by Product (Bar Chart)
  - Top 5 Customers by Revenue (Table)
  - Category-wise Sales Distribution (Donut Chart)

## Dashboard Visulization
<img src="Dashboard Image/Dashboard.png" width="500">


### 🔍 Key Insights
#### Sales Analysis Notes

### 🏆 Product Insights

  - Printer, Laptop, Keyboard are the top-selling products.
  - Printer & Monitor generate the highest profits.

### 👥 Customer Insights

  - The Top 5 customers contribute a major portion of revenue.
  - Business growth strategy should prioritize these high-value customers.

### 📦 Category Insights

  - Computers & Accessories dominate total sales.
  - hese product categories are performing strongly in the market.

### 💡 Business Takeaways

  - Focus marketing and promotions on high-profit products.
  - Improve strategies or pricing for low-performing products.
  - Maintain strong engagement with top revenue-generating customers.

### 📄 Project Files Included

  - File	Description
  - Sales Analysis.pbix	Power BI dashboard file
  - Dashboard Screenshot	High-quality PNG preview
  - Sales / Product / Customers CSVs	Raw dataset files
  - Sales Analysis Notes.docx	Documentation & insights

### ⭐ Conclusion

This project demonstrates a complete Excel → Power BI workflow using real-world business concepts:

  - Data cleaning in Power Query
  - Proper data modelling
  - Structured measure table
  - Professional dashboard design
  - Actionable business insights


This dashboard helps stakeholders understand sales performance, customer value, and product profitability at a glance.
