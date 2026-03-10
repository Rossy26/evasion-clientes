# 📊 Customer Churn Analysis

## 📌 Project Overview

This project analyzes **customer churn** in a telecommunications company to identify patterns and factors associated with customer cancellation.

Customer churn occurs when a client stops using a company's services. Understanding the variables that influence churn is essential for developing strategies that improve **customer retention and business performance**.

Through **data cleaning, transformation, and exploratory data analysis (EDA)**, this project aims to uncover insights that help explain customer behavior.

---

# 🎯 Objectives

The main goals of this project are:

- Understand the **distribution of customer churn**
- Identify **patterns and relationships** between customer characteristics and churn
- Explore how **categorical and numerical variables** influence customer cancellation
- Generate insights that support **business decision-making**

---

# 📂 Project Structure

```
customer-churn-analysis
│
├── data
│ └── telecom_churn_dataset.csv
│
├── notebooks
│ └── churn_analysis.ipynb
│
└── README.md

```
# 🧹 Data Cleaning and Processing

The dataset was prepared through several preprocessing steps:

- Standardizing text values (lowercase and removing extra spaces)
- Handling missing values
- Converting categorical variables to numerical values
- Binary encoding for **Yes/No variables**
- One-Hot Encoding for variables with multiple categories
- Creating a new variable called **Daily Charges**
