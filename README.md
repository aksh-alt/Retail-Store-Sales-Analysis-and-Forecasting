# Retail-Store-Sales-Analysis-and-Forecasting
Interactive Power BI dashboard analyzing retail store sales, profits, and forecasting future revenue.
![Screenshot 2025-05-31 094339](https://github.com/user-attachments/assets/4ee26a9d-41cb-4f8d-b9fd-6a15268e7209)




## : 📦 **Sales Insights and Forecasting for a Retail Superstore**

### 📌 Introduction

This Power BI dashboard was built to help retail decision-makers monitor overall sales performance, identify high-performing categories, analyze regional profit trends, and forecast future revenue. It delivers interactive insights into how products are selling, where profits are growing or declining, and what’s expected in the next 15 days.

The dashboard is fully dynamic, powered by DAX, Power Query, and advanced visuals.

---

### 🛠 Power BI Skills Used

The following Power BI features and techniques were utilized:

- 📊 **DAX Calculated Measures & Columns**
- 🧮 **Power Query Data Transformation**
- ⏳ **Date Functions & DATEDIFF**
- 🔁 **Data Model Relationships**
- 📉 **Forecasting with Line Charts**
- 🎯 **KPI Cards (Sales, Profit, Orders, Avg Ship Days)**
- 🎚 **Region-Based Slicers & Interactions**
- 🗺 **Map Visual for State-wise Sales**
- 📋 **Stacked Bar & Pie Charts**
- 🔝 **Top N Filter Logic** applied to show only top 3 values in selected visuals, keeping the dashboard focused and relevant

---

### 🗃️ Dataset Used

- 📥 **Source:** Kaggle / 
- 🧾 **Data Type:** Sales transaction data from a retail superstore  
- 📌 **Rows:** ~5,902  
- 📌 **Columns:** 21  

**Key Columns:**
- Order ID, Order Date, Ship Date, Ship Mode  
- Customer ID, Customer Name, Segment  
- Country, State, City, Region  
- Product ID, Category, Sub-Category, Product Name  
- Sales, Quantity, Discount, Profit  

---

## 📊 Dashboard Build

### 🔧 Data Preparation & Cleaning

- Cleaned and formatted columns using **Power Query**
- Renamed headers, unified text case, and removed nulls
- Used **Excel (Find & Replace)** for initial formatting
- Converted date formats and created calculated columns using:
  - `DATEDIFF()` – for Shipping Days
  - `CALCULATE()`, `SUMMARIZE()`, `COUNTROWS()`, `DIVIDE()`
  - **`SUMMARIZE()`** used for creating groups and aggregations in the **sales forecasting logic**

---

### 📈 Dashboards Created

#### 📊 Sales Overview Dashboard

- **KPI Cards:** Total Sales (1.57M), Orders (22K), Profit (175K), Avg Ship Days (4)
- **Visuals:**
  - Sales by Sub-Category, Category, and Region
  - Sales by Ship Mode
  - Sales by Payment Method
  - Sales & Profit by State (Map)
  - Profit & Sales Trends by Month & Year
- **Top 3 Filters:** Applied dynamic Top N logic to showcase the highest-performing values only, keeping visuals clean and decision-focused
  ![Screenshot 2025-05-31 094043](https://github.com/user-attachments/assets/3f2ea04e-1a21-4b1c-a8e4-441afa2a2386)
  
#### 🔮 Forecasting Dashboard

- Built using **Forecasting Line Charts**
- Shows:
  - **Sales History (2019–2020)**
  - **Projected Sales for 15 Days in 2021**
- Includes **Confidence Interval Ribbon** for future predictions

---

## 💡 Insights Gained

- 📉 **2020 had higher sales but lower profit** compared to 2019
- 🗺 **Eastern U.S. region led in both sales and profit**
- 📦 **Standard Class** was the most used shipping method
- 🖨 **Office Supplies** was the top-selling product category
- 🔮 **Forecasting model predicted a slight increase in sales** over the next 15 days

---

## 🧾 Conclusion

This project demonstrates how Power BI can be used not only for performance analysis but also for forward-looking decision-making through forecasting. By combining interactive dashboards, rich visuals, and time-series analysis, it helps retailers:

- Track sales & profit by category, region, and time
- Identify where to focus resources (e.g., top-selling states)
- Optimize shipping methods and inventory by analyzing trends
- Prepare for short-term sales performance using forecast data

---
