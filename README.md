# 📊 Sales Distributions Dashboard – Power BI

## Overview

This Power BI dashboard provides a comprehensive view of sales performance across different regions, product categories, and time periods. It is designed to help stakeholders understand sales trends, identify top-performing segments, and make data-driven decisions.

---

## 📁 File Details

- **File Name:** `Sales Distributions.pbix`
- **Tool Used:** Microsoft Power BI
- **Data Sources:** Internal sales data (transactional), product catalog, regional mapping, date dimension

---

## 🎯 Objectives

- Visualize total sales distribution across various dimensions
- Identify trends and performance metrics over time
- Enable dynamic filtering and drill-through for deeper analysis

---

## 📊 Key Features

- **Interactive Visuals:**
  - Sales by Region (Map or Bar Chart)
  - Product Category Breakdown (Pie or Donut Chart)
  - Monthly Sales Trend (Line Chart)
  - Top Products by Revenue (Bar Chart)
- **Dynamic Filters:**
  - Date Range
  - Region Selector
  - Product Category Selector
- **KPIs:**
  - Total Sales
  - Average Sales per Transaction
  - Monthly Growth Rate

---

## 🛠️ Data Preparation

- Cleaned missing/null values
- Created calculated columns (e.g., Year, Quarter)
- Added DAX measures:
  - `Total Sales = SUM(Sales[Amount])`
  - `Average Sales = AVERAGE(Sales[Amount])`
- Defined relationships between:
  - Sales ↔ Products
  - Sales ↔ Regions
  - Sales ↔ Dates

---

## 📈 Insights Provided

- Sales concentration by region
- Seasonal or monthly sales trends
- Top-performing categories and products
- Anomalies or outliers in performance

---

## 🚀 Future Improvements

- Add predictive analytics (e.g., forecasting)
- Implement row-level security (RLS) for user-based views
- Integrate with external sources (e.g., CRM or marketing platforms)
- Set up auto-refresh with cloud-based data sources

---

## 📌 Usage

1. Open the `.pbix` file in Power BI Desktop
2. Interact with slicers and charts for customized insights
3. Publish to Power BI Service for sharing with your team

---

## 🙋‍♂️ Contact

For any questions or collaboration, reach out to:  
**[Your Name]**  
**[Your Email or GitHub/LinkedIn]**

---
