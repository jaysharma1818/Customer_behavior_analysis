# Customer_behavior_analysis
🛒 Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.
The goal is to uncover insights into customer spending patterns, product preferences, discounts, and subscription behavior to support data-driven business decisions.

# The project follows a complete data analytics workflow:

Data Cleaning & EDA using Python
Business Analysis using MySQL
Interactive Visualization using Power BI

# 📊 Dataset Summary

Total Records: 3,900
Total Columns: 18

# Key Features:
Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type

# 🔍 Data Quality Notes:
37 missing values in the review_rating column
Missing values handled during data preprocessing

# 🧹 Exploratory Data Analysis (Python)
EDA and data preprocessing were performed using Python (Jupyter Notebook) with:
pandas
numpy
matplotlib
seaborn

# Key Steps:
Imported and explored data using df.info() and df.describe()
Checked and handled missing values in Review Rating using median values by product category
Standardized column names using snake_case

# Feature Engineering:
Created age_group by binning customer ages
Created purchase_frequency_days
Removed redundant column (promo_code_used)
Loaded the cleaned dataset into MySQL for further analysis

# 🗄️ Data Analysis Using SQL (MySQL)
Structured queries were written in MySQL to answer important business questions:
Revenue comparison by Gender
High-spending customers who used Discounts
Top 5 products by average review rating
Comparison between Standard vs Express shipping
Subscribers vs Non-Subscribers revenue analysis
Products most dependent on Discounts
Customer Segmentation (New, Returning, Loyal)

# Top 3 products per category

Relationship between Repeat Buyers & Subscription Status
Revenue contribution by Age Group

# 📈 Power BI Dashboard

An interactive Power BI dashboard was created to visually present insights such as:
Revenue distribution
Customer segments
Product performance
Subscription trends
Shipping type comparison
<img width="1239" height="672" alt="Screenshot 2025-12-21 102545" src="https://github.com/user-attachments/assets/f311aba1-494e-4412-8ffe-01a0d3869d2c" />


# 📁 Power BI file included: new_project.pbix
💡 Business Recommendations
📌 Increase subscription adoption with exclusive benefits
🎁 Implement customer loyalty programs
💰 Optimize discount strategies to protect profit margins

# ⭐ Promote top-rated and best-selling products

🎯 Use targeted marketing for high-revenue age groups and express shipping users

# 🛠️ Tools & Technologies Used

Python: Pandas, NumPy, Matplotlib, Seaborn
SQL: MySQL
Visualization: Power BI
IDE: Jupyter Notebook

# 📂 Repository Structure
📁 Customer-Shopping-Behavior-Analysis
│── 📄 README.md
│── 📄 Customer Shopping Behavior Analysis.pdf
│── 📊 new_project.pbix
│── 📓 Jupyter_Notebook.ipynb
│── 📄 SQL_Queries.sql
│── 📁 data

# 🚀 Key Highlights

End-to-end Data Analytics Project
Real-world business-focused SQL queries
Integration of Python, MySQL, and Power BI
Strong portfolio project for Data Analyst / Business Analyst roles
