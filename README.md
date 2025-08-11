# 🧾 Sales & Profit Dashboard

## 📌 Objective
Design a Power BI dashboard focusing on monthly profit trends and category performance.

## 📁 Dataset
File: Sample_Superstore_Sales.csv  
Columns: Order Date, Region, Category, Sales, Profit

## 🛠 Tools Used
- Power BI Desktop

## 🚀 Steps to Reproduce

1. Import the CSV file using Home > Get Data > Text/CSV.
2. Create a MonthYear column using: FORMAT([Order Date], "MMM-YYYY")
   - Sort it using a helper column if needed (MonthNum).
3. Visuals to Add:
   - 📈 Line Chart: Monthly Profit over MonthYear
   - 📊 Stacked Column Chart: Profit by Category & Region
   - 🍩 Donut Chart: Profit by Category
4. Add a Slicer:
   - Filter by Category or Region
5. Style:
   - Use colors to emphasize low vs high profitability
