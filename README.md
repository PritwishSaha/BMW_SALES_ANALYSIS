# 🚗 BMW Sales Analysis Dashboard

<p align="center">
  <img src="Screenshot 2026-07-04 233322.png" alt="BMW Sales Analysis Dashboard" width="100%">
</p>

## 📌 Project Overview

This project analyzes BMW vehicle sales data using Python and Power BI. The dataset was downloaded from Kaggle, cleaned and transformed using Pandas and NumPy, and then visualized through an interactive Power BI dashboard.

The workflow consists of three main stages:

1. Downloading the BMW dataset from Kaggle
2. Cleaning and transforming the data using Python (Pandas & NumPy)
3. Building an interactive business intelligence dashboard in Power BI

The dashboard helps stakeholders understand sales performance, identify top-performing models, analyze regional demand, and evaluate customer preferences.

---

## 🎯 Project Objectives

- Analyze BMW sales performance
- Identify top revenue-generating models
- Track sales trends over time
- Understand customer fuel and transmission preferences
- Discover high-performing regions
- Evaluate vehicle price segments
- Generate actionable business insights

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|--------|---------|
| Python | Data Cleaning & Transformation |
| Pandas | Data Manipulation |
| NumPy | Data Processing |
| Power BI | Dashboard Development |
| Kaggle | Data Source |
| GitHub | Project Portfolio |

---

## 📂 Project Workflow

### 1️⃣ Data Collection

- Downloaded BMW sales dataset from Kaggle
- Imported dataset into Python environment

### 2️⃣ Data Cleaning

Performed data preprocessing using Pandas and NumPy:

- Removed duplicates
- Handled missing values
- Checked data types
- Cleaned categorical variables
- Created calculated fields
- Prepared dataset for reporting

Example libraries used:

```python
import pandas as pd
import numpy as np
```

### 3️⃣ Feature Engineering

Created business metrics such as:

- Revenue
- Price Segments
- Sales Classification
- Revenue Analysis Measures

Revenue Calculation:

```python
df["Revenue"] = df["Price_USD"] * df["Sales_Volume"]
```

### 4️⃣ Dashboard Development

Imported the cleaned dataset into Power BI and created an interactive dashboard featuring:

- KPI Cards
- Line Charts
- Bar Charts
- Donut Charts
- Treemaps
- Matrix Tables

---

## 📊 Dashboard KPIs

- Total Revenue
- Total Sales Volume
- Average Vehicle Price
- Total Models

---

## 📈 Key Business Questions Answered

### Revenue Analysis

- Which BMW models generate the highest revenue?
- Which region contributes the most revenue?
- Which price segment contributes the most revenue?

### Sales Analysis

- How many vehicles were sold in total?
- Which BMW models have the highest sales volume?
- Which region sells the most vehicles?
- How have sales changed over the years?

### Customer Preference Analysis

- Which fuel type is most preferred by customers?
- Which transmission type performs better?
- Which color is most popular among customers?

### Advanced Insights

- What factors are common among high-sales vehicles?
- Do expensive BMW models sell more or less than cheaper models?

---

## 📌 Dashboard Features

✔ Executive KPI Summary

✔ Revenue Analysis

✔ Sales Trend Analysis

✔ Product Performance Analysis

✔ Fuel Type Analysis

✔ Transmission Analysis

✔ Color Preference Analysis

✔ Price Segment Analysis

✔ High-Sales Vehicle Insights

---

## 📸 Dashboard Preview

The dashboard provides a comprehensive overview of BMW sales performance through interactive visualizations and business-focused KPIs.

---

## 🚀 Business Insights

- Premium and Luxury segments contribute significantly to revenue.
- Customer preferences vary by fuel type and transmission.
- Certain BMW models consistently outperform others in revenue generation.
- Regional performance highlights key growth opportunities.
- Sales trends reveal market demand patterns over time.

---

## 📁 Repository Structure

```text
BMW-Sales-Analysis/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── dashboard/
│   └── BMW_Sales_Dashboard.pbix
│
├── screenshots/
│   └── Screenshot 2026-07-04 233322.png
│
├── README.md
│
└── requirements.txt
```

---

## 👨‍💻 Author

**Pritwish**

Engineering Student | Aspiring Data Analyst

### Skills Demonstrated

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- Business Intelligence
- Power BI Dashboarding
- KPI Development
- Data Visualization
- Business Reporting

---

⭐ If you found this project useful, consider giving the repository a star.