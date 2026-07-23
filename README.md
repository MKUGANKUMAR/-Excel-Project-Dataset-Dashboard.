# 🚴 Bike Sales Data Analysis & Excel Dashboard

An end-to-end Excel data analysis project exploring customer demographics and purchasing behavior to uncover key drivers behind bicycle sales.

---

## 📌 Project Overview

Understanding demographic patterns is essential for optimizing marketing strategies and targeting high-conversion customer segments. This project analyzes a dataset of **1,000 customer records** to identify how factors such as **income levels, age groups, commute distance, and geographic region** influence bike purchasing decisions.

📥 <a href="https://github.com/MKUGANKUMAR/-Excel-Project-Dataset-Dashboard./blob/71fb639632a81c45ab1bb80dc3216e394e8b1cba/Excel%20Project%20Dataset.xlsx">Click to Download the Excel Data</a>

---

## 📊 Key Performance Indicators (KPIs)

* 🎯 **Total Conversion Rate**: **48.1%** (481 out of 1,000 customers purchased a bike)
* 💵 **Average Buyer Income**: **$57,963** vs. **$54,875** for non-buyers (buyers earn **5.6% more** on average)
* 🏃 **Top Performing Target Segment**: **Adults aged 25–45** with a **51.9%** conversion rate (299 buyers)
* 🚗 **Optimal Commute Distance**: **0–1 Miles** generated the highest buyer volume (200 buyers, **54.6% conversion**)
* 🗺️ **Top Converting Region**: **Pacific Region** achieved the highest regional conversion rate (**58.9%**)

---

## 🖼️ Dashboard Preview

<a href="https://github.com/MKUGANKUMAR/-Excel-Project-Dataset-Dashboard./blob/main/Screenshot%202026-07-23%20080302.png">Dashboard Screenshot

> *Note: Open the Excel file locally to interact with dynamic slicers for Region, Education, and Marital Status.*

---

## 🛠️ Tools & Technologies Used

* **Microsoft Excel**: Data Cleaning, Pivot Tables, Formulas & Dashboarding
* **Data Processing**: Duplicate removal, text standardization, and custom conditional binning

---

## 🧹 Data Cleaning & Preparation Process

To ensure data integrity prior to analysis, the following cleaning steps were performed:

1. **Duplicate Removal**: Identified and removed duplicate customer entries to maintain unique demographic records.
2. **Column Standardization**: Cleaned up marital status (`Marriedarital Singletatus`) and gender records for uniform formatting.
3. **Data Binning**:
   * Created a custom **Age Bracket** column to categorize continuous age values into structured demographic segments (`Adult 25 - 45`, `Middle Age Persons`, `Aged Persons 50+`, `Older Persons 60+`).
   * Standardized commute ranges into ordered categories for logical sorting.

---

## 🔍 Detailed Findings & Insights

* 💰 **Income Impact**: Customers who purchased a bike had a higher average income (**$57,963**) compared to non-buyers (**$54,875**), indicating higher disposable income positively correlates with purchases.
* 📏 **Commute Distance**: The highest conversion rate occurred among individuals with short commutes (**0–1 miles**), while purchase likelihood decreased significantly for long commutes (**>10 miles**).
* 👥 **Age Demographics**: The **Adults (25–45)** demographic segment represents the largest customer base and the highest volume of bike buyers.
* 🌍 **Regional Trends**: The **Pacific** region demonstrated the highest conversion percentage, while **North America** generated the largest total customer base.

---

## 📁 Repository Structure

```text
├── Excel Project Dataset.xlsx     # Complete Excel file (Data, Pivots, Dashboard)
├── dashboard_screenshot.png        # Dashboard screenshot for preview
└── README.md                       # Project documentation
