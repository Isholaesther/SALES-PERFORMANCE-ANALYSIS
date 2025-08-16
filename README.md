# 📊 Sales Performance Analysis Dashboard  

This repository contains an Excel project analyzing sales performance from a dataset of retail transactions.  
The analysis includes data cleaning, exploratory analysis, KPI generation, and dashboard visualization.  

---

## 📑 Table of Contents  
1. [Project Overview](#project-overview)  
2. [Data Cleaning](#data-cleaning)  
3. [Exploratory Analysis](#exploratory-analysis)  
4. [Stakeholder Questions & Insights](#stakeholder-questions--insights)  
5. [Dashboard](#dashboard)  
6. [Executive Summary](#executive-summary)  
7. [Limitations](#limitations)  
8. [About the Author](#about-the-author)  
9. [Conclusion](#conclusion)  

---

## 📌 Project Overview  
- **Initial Dataset Size:** 200 records  
- **Final Dataset Size (after cleaning):** 96 records  
- **Tool Used:** Microsoft Excel  
- **New Columns Created:**  
  - `Month Name` → extracted from Sale Date  
  - `Total Sales` → calculated as `Quantity Sold × Price`  

The analysis was guided by stakeholder questions, focusing on product performance, sales trends, and return patterns.

---

## 🧹 Data Cleaning  
Steps taken to prepare the dataset:  
- Removed duplicate rows  
- Corrected inconsistent date formats  
- Standardized product names and categories  
- Filled or removed rows with missing values  
- Removed rows with missing **Sale Date** or **Status** (essential for analysis)  
- Created new calculated columns (`Month Name`, `Total Sales`)  

After cleaning, **104 invalid/missing records** were dropped, leaving **96 valid rows**.

---

## 🔍 Exploratory Analysis  
Performed the following:  
- Revenue and sales by product and category  
- Returns analysis by product and location  
- Average pricing within categories  
- Seasonal patterns using `Month Name`  
- Dashboard creation for KPI visualization  

---

## ❓ Stakeholder Questions & Insights  

### 1. Missing Records  
- **104 records** had missing `Sale Date` or `Status`.  
- **Impact:** Sales trends and return rates could have been misrepresented if these were included.  

### 2. Total Revenue by Product & Category  
- Revenue = `Price × Quantity Sold`.  
- **Top categories by revenue:** Appliances, Electronics.  
- **Top products by revenue:** Blender, Fridge.  

### 3. Sales Trends Over Time  
- After standardizing dates, sales peaked in **March and July**, suggesting possible seasonality.  

### 4. Highest & Lowest Store Sales  
- **Highest:** Lagos  
- **Lowest:** Port Harcourt  

### 5. Average Price per Category  
- Calculated using `AVERAGEIF()`.  
- Outliers identified, especially in Appliances.  

### 6. Best Performing Products  
- **By Quantity Sold:** Blender, Shirt  
- **By Revenue:** Fridge, Laptop  

### 7. Overstocking/Understocking  
- **Overstocked:** Microwave (low sales, high stock).  
- **Risk of understocking:** Blender (high demand).  

### 8. Highest Return Rates by Location  
- **Ibadan and Abuja** showed higher percentages of returns.  
- Possible reasons: supply chain inefficiencies or product quality issues.  

### 9. Dashboard  
- Interactive Excel dashboard created.  
- Includes slicers for **Status, Month, and Category** to enable interactivity.  

### 10. Frequently Returned Products  
- Toasters and Shirts recorded the highest return counts.  
- Likely causes: product defects, sizing/quality issues.  

### 11. Product Performance Across Locations  
- **Blender:** strongest in Lagos.  
- **Electronics:** stronger in Abuja.  
- **Port Harcourt:** weakest overall performance.  

### 12. Seasonal Patterns  
- Peaks in **March** and **July** indicate potential seasonal demand.  

### 13. Impact of Returns on Revenue  
- Returns represented about **46% of transactions**, significantly cutting into net revenue.  

### 14. Relationship Between Category, Price & Sales  
- **Lower-priced items (e.g., Shirts):** high volume, low revenue.  
- **Higher-priced items (e.g., Appliances):** low volume, high revenue.  

---

## 📊 Dashboard  
The Excel dashboard includes:  
- Revenue by category and location  
- Top/Bottom 5 products  
- Sales trend over time  
- Return rates analysis  
- Product performance breakdown  

*[Dashboard Screenshots:]*  
(Annotation 2025-08-16 092957.png)

---

## 📌 Executive Summary  
This project presents an interactive Excel dashboard designed to analyze and visualize key performance indicators (KPIs).  
The dashboard incorporates features such as pivot tables, slicers (connected across charts), dropdown filters, and textboxes with the Nigerian Naira (₦) symbol.  
It provides stakeholders with insights into sales performance, regional comparisons, and overall business trends, enabling data-driven decision-making.  

---

## ⚠️ Limitations  
- The dashboard relies on static data and requires manual updates unless connected to a live source.  
- Excel has formatting restrictions compared to BI tools like Power BI.  
- Assumes users understand how to use slicers and dropdowns.  
- Performance may degrade with larger datasets.  

---

## 👩‍💻 About the Author  
**Esther Anuoluwapo Ishola** is a Microbiology graduate turned data analyst with growing expertise in Excel, SQL, and Power BI.  
She is passionate about transforming raw data into actionable insights and helping businesses make informed decisions through data-driven storytelling.  

---

## ✅ Conclusion  
The Excel-based sales performance dashboard effectively answers stakeholder questions, highlights product performance, and identifies revenue drivers and risks.  
While limited by Excel’s capabilities, it demonstrates how a cleaned dataset can drive meaningful business insights.  

---
