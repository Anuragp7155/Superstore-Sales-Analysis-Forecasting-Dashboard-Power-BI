# 📊 Superstore Sales Analysis & Forecasting Dashboard

## 📌 Project Overview
This project is an end-to-end **Power BI Sales Analytics Dashboard** built using the **Superstore Sales Dataset**. The dashboard transforms raw sales data into meaningful business insights through interactive visualizations, KPI tracking, geographic analysis, and sales forecasting.

The objective of this project is to analyze **2 years of historical sales data**, identify key performance trends, and forecast future sales to support data-driven business decisions.

---

## 🎯 Objectives
- Analyze historical sales performance.
- Track key business KPIs.
- Identify high-performing regions, categories, and customer segments.
- Perform time-series analysis on sales and profit trends.
- Forecast future sales using Power BI forecasting techniques.
- Build an interactive dashboard for business stakeholders.

---

## 🛠️ Tools & Technologies
- Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Data Visualization
- Time Series Forecasting

---

## 📂 Dataset Information
The dataset contains retail sales transaction records, including:

- Order Date
- Ship Date
- Customer Segment
- Region
- State
- Category
- Sub-Category
- Sales
- Quantity
- Profit
- Ship Mode
- Payment Mode

---

## 🧹 Data Cleaning & Preparation
Data preprocessing was performed using **Power Query Editor**:

- Checked column quality and missing values.
- Corrected data types.
- Removed unnecessary columns.
- Handled inconsistent records.
- Created calculated fields required for analysis.

---

## 📊 Dashboard Features

### KPI Cards
The dashboard includes key performance indicators such as:

- 💰 Total Sales: **1.57M**
- 📦 Total Quantity Sold: **22K**
- 📈 Total Profit: **175.26K**
- 🚚 Average Delivery Time: **4 Days**

### Sales Analysis
- Monthly Sales Trends
- Year-over-Year Sales Comparison
- Sales by Region
- Sales by State
- Sales by Category
- Sales by Sub-Category

### Profit Analysis
- Monthly Profit Trends
- State-wise Profit Contribution
- Category-wise Profit Analysis

### Customer Analysis
- Sales by Customer Segment
- Sales by Payment Mode
- Sales by Shipping Mode

### Geographic Analysis
- Interactive State-wise Sales Map
- Regional Performance Comparison

### Interactive Filtering
Users can dynamically filter the dashboard by:
- Region
- Category
- Customer Segment
- State

---

## 📈 DAX Calculations

### Average Delivery Time
```DAX
Average Delivery Days =
DATEDIFF(
    Orders[Order Date],
    Orders[Ship Date],
    DAY
)
```

### Sales Aggregation Table
```DAX
Sales Summary =
SUMMARIZE(
    Orders,
    Orders[Order Date],
    "Total Sales",
    SUM(Orders[Sales])
)
```

---

## 🔮 Sales Forecasting

A dedicated forecasting dashboard was developed using Power BI's built-in forecasting functionality.

### Forecast Features
- 15-Day Sales Forecast
- Historical Sales Trend Analysis
- 95% Confidence Interval
- Upper and Lower Forecast Bounds
- Future Sales Projection

This forecasting model helps businesses estimate future demand and make informed inventory and operational decisions.

---

## 📌 Key Insights

### Sales Insights
- California generated the highest sales among all states.
- The West region contributed the largest share of total sales.
- Consumer customers accounted for nearly half of total sales.

### Profit Insights
- October and December showed strong profit growth.
- Technology and Office Supplies were major revenue-generating categories.

### Shipping Insights
- Standard Class shipping mode generated the highest sales volume.

### Forecast Insights
- Future sales are projected to maintain a positive growth trend.
- Confidence intervals provide visibility into forecast uncertainty and risk.

---

## 📷 Dashboard Preview

### Main Dashboard
![Sales Dashboard](https://github.com/Anuragp7155/Superstore-Sales-Analysis-Forecasting-Dashboard-Power-BI/blob/main/Sales%20Dashboard.png?raw=true)

### Sales Forecast Dashboard
![Forecast Dashboard](https://github.com/Anuragp7155/Superstore-Sales-Analysis-Forecasting-Dashboard-Power-BI/blob/main/Forecast%20Visual.png?raw=true)

---

## 📁 Project Structure

```text
Superstore-Sales-Dashboard/
│
├── Dataset/
│   └── SuperStore Sales DataSet.xlsx
│
├── Dashboard Screenshots/
│   ├── Sales Dashboard.png
│   └── Forecast Visual.png
│
├── Power BI Dashboard/
│   └── Superstore_Sales_Dashboard.pbix
│
└── README.md
```

---

## 🚀 Business Impact
This dashboard helps organizations:

- Monitor business performance effectively.
- Identify profitable products and regions.
- Improve strategic decision-making.
- Forecast future sales demand.
- Optimize inventory planning and resource allocation.

---

## 👨‍💻 Author

**Anurag Patil**

Aspiring Data Analyst skilled in:
- Power BI
- SQL
- Python
- PostgreSQL
- Data Visualization
- Business Intelligence

### Connect with Me
- LinkedIn: www.linkedin.com/in/anurag-patil561

---

⭐ If you found this project useful, don't forget to star the repository.
