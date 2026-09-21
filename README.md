# 📱 PhonePe Transaction & Demographic Analysis — Python

> End-to-end Python analysis of PhonePe transaction, user, device, and demographic data across Indian states and districts to identify transaction trends, user behavior, device patterns, and demographic relationships.

---

## 📌 Project Overview

This project analyzes PhonePe transaction and demographic data using Python to understand digital payment trends across India.

The analysis covers transaction volumes, transaction values, registered users, device usage, app engagement, and demographic relationships at both state and district levels.

The project also includes data cleaning, exploratory data analysis, visualization, correlation analysis, and business recommendations.

---

## 🎯 Business Objectives

- Analyze transaction trends across Indian states and districts.
- Identify states and regions with high transaction activity.
- Understand registered users and device usage patterns.
- Study the relationship between population demographics and transaction volume.
- Identify data quality and reconciliation gaps.
- Generate actionable insights for digital-payment adoption and engagement.

---

## 📂 Dataset

The project uses multiple datasets containing transaction, user, device, and demographic information.

### Excel Sheets Used

- `State_Txn and Users`
- `State_TxnSplit`
- `State_DeviceData`
- `District_Txn and Users`
- `District Demographics`

A district-to-state mapping CSV is included to support geographical analysis.

---

## 🧹 Data Preparation

The analysis includes:

- Loading data from Excel and CSV files using Pandas.
- Standardizing column names.
- Removing unnecessary spaces from column names.
- Checking data consistency.
- Preparing datasets for state-level and district-level analysis.
- Combining transaction and demographic information for deeper analysis.

---

## 🔍 Analysis Performed

### Transaction Analysis
- State-wise transaction volume analysis.
- Transaction amount and value trends.
- Yearly and quarterly transaction patterns.
- Identification of high-performing states.

### User Analysis
- Registered user analysis across states.
- Registered users compared with population.
- Identification of adoption patterns.

### Device Analysis
- Analysis of device usage across users.
- Identification of commonly used device brands.

### Demographic Analysis
- District-level population analysis.
- Population density vs transaction volume.
- Correlation analysis between demographic variables and digital-payment activity.

### Data Quality Analysis
- State vs district-level reconciliation.
- Identification of potential data gaps and inconsistencies.

---

## 📊 Key Findings

### 1. Highest Transaction Volume
Karnataka recorded the highest total transaction volume in the available state-level data:

**2,981,044,533 transactions**

### 2. Highest Weighted Average Transaction Value
Ladakh recorded the highest weighted average transaction value (ATV):

**₹3,514.15**

### 3. Population Density & Transaction Volume
The Pearson correlation between district population density and transaction volume was:

**0.4188**

This indicates a moderate positive relationship between population density and transaction activity.

### 4. App Engagement
App opens can be monitored alongside transaction activity to identify changes in user engagement and potential monetization opportunities.

### 5. Data Reconciliation
Regular reconciliation between district-level and state-level datasets can help identify data quality gaps and improve reporting accuracy.

---

## 💡 Business Recommendations

- Strengthen digital-payment infrastructure in high-potential regions.
- Use state and district-level trends to design localized campaigns.
- Monitor app opens alongside transactions to understand user engagement.
- Perform regular district-to-state reconciliation to improve data quality.
- Automate reconciliation and reporting workflows for faster analysis.

---

## 📸 Analysis Visualizations

### 📊 Transaction Trends

<img width="1189" height="590" alt="transaction-trends" src="https://github.com/user-attachments/assets/9c6c8cb1-a791-418f-a81a-434f28381705" />

State-level transaction analysis highlighting changes in transaction volume and transaction amount over time.

---

### 📈 Population Density vs Transaction Volume

<img width="788" height="590" alt="density-vs-transaction-volume" src="https://github.com/user-attachments/assets/e662507d-64f2-48d8-8d93-c5662d555cb0" />

Correlation analysis examining the relationship between district population density and transaction volume.

---

### 📱 Registered Users to Population Ratio

<img width="1390" height="590" alt="registered-users-population-ratio" src="https://github.com/user-attachments/assets/f1154d51-979c-4753-a957-9abc52e0ab58" />

State-level comparison of registered users relative to population to understand digital-payment adoption patterns.

---

## 🛠️ Tools & Skills

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Correlation Analysis
- Business Analysis

---

## 📓 Notebook Workflow

The Jupyter Notebook follows an end-to-end analytical workflow:

```text
Data Loading
     ↓
Data Cleaning & Preparation
     ↓
Exploratory Data Analysis
     ↓
Transaction Analysis
     ↓
User & Device Analysis
     ↓
Demographic Analysis
     ↓
Correlation Analysis
     ↓
Visualization
     ↓
Business Insights & Recommendations
```

---

## 📂 Project Structure

```text
phonepe-data-analyst-project/
│
├── PhonePe_Data_Analyst_Project.ipynb
├── PhonePe_Data.xlsx
├── district_name_code_mapping.csv
├── README.md
│
└── screenshots/
    ├── transaction-trends.png
    ├── density-vs-transaction-volume.png
    └── registered-users-population-ratio.png
```
