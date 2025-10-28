# Amazon-Sales-Analysis
Amazon Sales Analysis &amp; Interactive Dashboard using Power BI
# 📊 Amazon Sales Analysis & Power BI Dashboard

## 🔍 Project Overview
This project demonstrates **end-to-end Amazon sales data analysis** and visualization using **Microsoft Power BI**. The dashboard provides actionable insights into revenue trends, product performance, and regional sales distribution.

---

## 🛠 How I Built This Dashboard

### 1️⃣ **Data Collection**
- Source: Amazon sales dataset (CSV format)
- Columns included: `Order ID`, `Product Category`, `Sales`, `Quantity`, `Region`, `Order Date`

### 2️⃣ **Data Cleaning & Transformation**
- Removed duplicates and handled missing values using **Power Query**
- Converted date columns into proper **Date/Time format**
- Created calculated columns for:
  - **Month & Year**
  - **Profit Margin**
  - **Sales Category**

### 3️⃣ **Data Modeling**
- Built a **Star Schema**:
  - **Fact Table**: Sales transactions
  - **Dimension Tables**: Product, Region, Date
- Established relationships for accurate filtering

### 4️⃣ **DAX Measures**
- **Total Sales** = `SUM(Sales)`
- **Total Quantity** = `SUM(Quantity)`
- **Profit Margin %** = `(Profit / Sales) * 100`
- **Year-to-Date Sales** using `TOTALYTD()`

### 5️⃣ **Dashboard Design**
- Used **Power BI visuals**:
  - **Clustered Column Chart** for category-wise sales
  - **Map Visualization** for regional performance
  - **Cards & KPIs** for quick metrics
  - **Slicers** for dynamic filtering (Region, Category, Date)
- Applied **Themes & Color Palette** for a professional look

---

## ✅ Key Insights
- Top-selling categories and regions identified
- Seasonal trends in sales highlighted
- KPIs for quick decision-making

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1f529e2b-5021-41b4-a2a9-5c2ac70b5100" />


## 🔗 Live Dashboard
View on Power BI Service


