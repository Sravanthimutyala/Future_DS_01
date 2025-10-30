# Future_DS_01
# 🛍️ E-Commerce Sales Dashboard | Power BI Project

## 📖 Overview
This project is part of my internship with **Future Interns**, focused on analyzing e-commerce sales performance using **Power BI**.  
The goal was to transform raw transactional data into meaningful business insights that highlight **best-selling products, sales trends, high-revenue categories,** and **regional performance**.

---

## 🎯 Task Description (Given by Future Interns)
**Task:** Analyze e-commerce data to identify best-selling products, sales trends, and high-revenue categories using Power BI.  
**Skills Gained:** Data Cleaning, DAX, Trend Analysis, Business Storytelling  
**Deliverable:** An interactive dashboard with visuals and insights for business decisions.

---

## 🧩 Objectives
- Identify **top-selling categories and sub-categories**
- Analyze **state-wise sales and profit distribution**
- Discover **preferred payment modes**
- Visualize **monthly sales and profit trends**
- Provide actionable insights for **business decision-making**

---

## 📊 Dashboard Highlights

### 🔹 KPIs
- **Total Sales (Amount)**
- **Total Profit**
- **Total Orders**
- **Profit Percentage**

### 🔹 Visual Insights
- **Sales by Category & Payment Mode** — Understand customer payment preferences by category  
- **Sales Trend by Month** — Observe monthly performance and seasonality  
- **Profit by Sub-Category** — Identify most and least profitable product lines  
- **Sales & Profit by State (Map View)** — Explore regional performance visually  
- **Payment Mode Distribution** — Analyze how customers prefer to pay  
- **Order Details Table** — Display transactional-level insights

---

## ⚙️ Tools & Techniques Used
- **Microsoft Power BI**
- **Data Cleaning** (Power Query Editor)
- **Data Modeling** (Relationships between tables: Orders & Details)
- **DAX (Data Analysis Expressions)**
  - Calculated Measures:  
    - `Total Sales = SUM(Details[Amount])`  
    - `Total Profit = SUM(Details[Profit])`  
    - `Profit% = DIVIDE(SUM(Details[Profit]), SUM(Details[Amount]))`  
    - `Total Orders = COUNT(Orders[Order ID])`
- **Interactive Filters** for State, Month, Category, and Payment Mode

---

## 🗺️ Insights Derived
📍 **Top Performing States:** Maharashtra, Tamil Nadu, Uttar Pradesh  
💸 **Most Popular Payment Mode:** Credit Card  
🛒 **Best-Selling Category:** Electronics  
📈 **Sales Trend:** Peaks observed in March and December, indicating festive/seasonal buying patterns.  
💡 **Key Takeaway:** Electronics and clothing drive major revenue; states with higher digital payment adoption also show higher order value.

---

## 💻 Project Workflow
1. **Data Cleaning** — Removed duplicates, fixed inconsistent formats, and standardized fields  
2. **Data Modeling** — Established relationships between `Orders` and `Details` tables  
3. **Measure Creation** — Built calculated columns and DAX measures for analysis  
4. **Visualization Design** — Created KPIs, charts, map visuals, and slicers  
5. **Dashboard Formatting** — Used gradient themes, alignment grids, and business-friendly titles  
6. **Storytelling & Insights** — Highlighted actionable findings for strategic decisions  

---

## 🧠 Learnings
- Applying **data storytelling** to support business decisions  
- Building **interactive dashboards** that combine analytics with design  
- Enhancing **Power BI proficiency** with DAX, filters, and visualization best practices  

---

## 👩‍💻 Intern Details
**Internship:** Future Interns  
**Role:** Data Science and Analytics
**Duration:** October 2025  
**Project:** E-Commerce Sales Report Dashboard   

---

> _"Every dataset hides a decision — Power BI helps us find it."_  

---


