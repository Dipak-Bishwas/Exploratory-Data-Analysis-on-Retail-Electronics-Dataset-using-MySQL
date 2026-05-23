# 📊 Electronics Retail Data Analysis using SQL

## 📌 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on a retail electronics dataset using **MySQL**. The goal is to clean raw product data, engineer meaningful features, and extract business insights related to pricing, discounts, ratings, and customer engagement.

---

## 🎯 Objectives
- Clean and preprocess raw retail electronics dataset using SQL
- Perform feature engineering to create analytical variables
- Conduct exploratory data analysis (EDA) using SQL queries
- Identify pricing patterns, discount behavior, and rating trends
- Extract business insights using statistical and analytical SQL techniques

---

## 📂 Dataset Information
The dataset contains information about electronics products including:
- Product Title
- Price
- Discount Type
- Ratings & Reviews
- Sub Category
- Currency Information

---

## 🛠️ Tools & Technologies Used
- MySQL
- SQL (DDL, DML, Aggregations, Window Functions)
- Data Cleaning Techniques
- Feature Engineering using SQL
- Statistical Analysis (Covariance, Correlation, Percentiles)

---

## 🧹 Data Cleaning & Feature Engineering
Key transformations performed:
- Removed currency symbols and special characters from price column
- Converted price ranges ("through") into numerical values
- Extracted numerical ratings from text-based rating column
- Created new features such as:
  - `Average_Rating`
  - `Reviews_Count`
  - `Discount_Given`
  - `MRP`
  - `Brandname`
- Standardized discount categories into meaningful groups

---

## 📊 Exploratory Data Analysis (EDA)
Performed various SQL-based analyses:
- Descriptive statistics (MIN, MAX, AVG, STD)
- Null value detection
- Category-wise distribution analysis
- Price distribution using bucket/histogram logic
- Brand-wise and sub-category analysis

---

## 📈 Statistical Analysis
Advanced analytical techniques used:
- Covariance between ratings and reviews
- Correlation analysis
- Percentile-based price distribution
- Outlier detection using IQR method
- Regression slope estimation between price and MRP

---

## 📌 Key Insights
- Identified pricing distribution across different product segments
- Found relationship between reviews and product ratings
- Detected outliers in high-priced electronics categories
- Analyzed discount patterns and their impact on pricing
- Evaluated brand-level pricing consistency

---

## 🧠 Skills Demonstrated
- SQL Data Cleaning & Transformation
- Exploratory Data Analysis (EDA)
- Analytical Thinking
- Business Intelligence using SQL
- Statistical Computation in SQL

---
