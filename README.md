# 📊 Multi-Dashboard Sales & Profitability Analysis (2014–2017)

- **Tool Used:** Power BI  
- **Role:** Data Analyst / BI Developer  
- **Scope:** Sales, Discounts, Profit Margins, and Trend Analysis  
- **Data Period:** 2014 – 2017  

---

## 🛠️ Tools & Workflow

- **Data Cleaning:** Python (Pandas in Jupyter Notebook)  
- **Data Modeling:** Star schema  
  - Fact table  
  - Dimensions: Time, Geography, Product, Customer, Ship Mode  
- **Visualization & DAX Calculations:** Power BI  
- **Custom Metrics:**  
  - Average Discount per Order  
  - Profit Margin  
  - Performance Flag  

---

## 📌 Project Overview

This multi-dashboard project provides a **holistic view of sales performance** across customer segments, product categories, and geographic locations. It analyzes the **impact of discounts on profit margins** and uncovers **seasonal trends**, helping inform strategic business decisions.

- **Dataset Source:** Superstore Dataset (commonly used in tools like Power BI and Tableau)  
- **Dataset Type:** Transactional Sales Data  
- **Period Covered:** 2014–2017  
- **Key Fields:** `Order Date`, `Segment`, `Category`, `Sub-Category`, `City`, `Sales`, `Profit`, `Discount`

---

## 📊 Dashboards Included

### 1. Average Discount & Profit Margin Analysis  
**Purpose:** Evaluate how discounts affect profit margins across segments and sub-categories.  

**Key Insights:**  
- The **Consumer segment** had the highest price sensitivity and aggressive discounting in 2014.  
- The **Appliances sub-category** maintained high margins despite discounts.  
- **Corporate and Home Office** segments showed improved efficiency over time.

---

### 2. Sales Performance & Geographic Analysis  
**Purpose:** Identify top-performing sub-categories, cities, and customer segments.  

**Key Insights:**  
- **Total Sales:** $2.30M | **Profit:** $286.4K  
- **Top Contributors:** New York City, Phones, and Paper  
- **Tables sub-category** had high sales but negative profit  
- The **Consumer segment** generated over 50% of total sales and profits

---

### 3. Trend Analysis Dashboard  
**Purpose:** Track sales and profit trends over months, quarters, and years.  

**Key Insights:**  
- Peak performance in **Q4**, especially **November and December**  
- Mid-year slowdown observed in **June–July**  
- Used **trendline and waterfall charts** for intuitive insights  
- **Slicers** enabled deep filtering by year, sub-category, and segment

---

## 💡 Business Recommendations

- **Optimize discounting** in the Consumer segment to boost profitability  
- Reevaluate pricing for low-margin, high-sales sub-categories like **Tables**  
- Prioritize inventory and promotions in **Q4** (highest performance period)  
- Replicate pricing strategies of high-margin items like **Copiers** and **Appliances**

---

## 📁 Files

- `/notebooks/` — Jupyter Notebook used for initial data cleaning  
- `/dashboards/` — Power BI dashboard screenshots and reports  

---

## ✅ Skills Demonstrated

- KPI tracking & customer segmentation  
- Time-series analysis & trend forecasting  
- Geographic and category-based performance benchmarking  
- Dashboard interactivity using filters and slicers  
- Business insight communication with storytelling visuals