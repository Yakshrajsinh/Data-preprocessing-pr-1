# 📊 Customer Churn Prediction – Data Preprocessing & EDA Project

## 📌 Project Overview

This project focuses on **data preprocessing, feature engineering, and exploratory data analysis (EDA)** on a customer purchase dataset collected from multiple sources.

The goal is to prepare the dataset for machine learning and frame a **Customer Churn Prediction** problem.

---

## 🎯 Objective

* Clean and preprocess raw data
* Perform exploratory data analysis (EDA)
* Handle missing values and inconsistencies
* Engineer useful features
* Generate a profiling report
* Prepare dataset for ML model

---

## 🧠 Problem Statement

Build a **Machine Learning classification model** to predict whether a customer will **churn** based on:

* Purchase behavior
* Income
* Demographics
* Engagement patterns

**Target Variable:** `Churn (Yes/No)`

---

## 🗂️ Dataset Description

| Column                 | Description         |
| ---------------------- | ------------------- |
| Customer_ID            | Unique customer ID  |
| Age                    | Customer age        |
| Gender                 | Male/Female         |
| Income                 | Annual income       |
| Purchases              | Number of purchases |
| Total_Spend            | Total spending      |
| Last_Purchase_Days_Ago | Recency of purchase |
| Membership_Years       | Customer loyalty    |
| Preferred_Category     | Product category    |
| Churn                  | Target variable     |

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQLite
* Requests (API)
* YData Profiling

---

## 📥 Data Acquisition

Data was collected from multiple sources:

* CSV file using Pandas
* JSON file parsing
* SQL database using SQLite
* API data using REST API

---

## 🧹 Data Cleaning

* Handled missing values using:

  * Mean (numerical)
  * Mode (categorical)
* Removed duplicates
* Fixed inconsistent data types
* Dropped irrelevant columns
* Standardized column names

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Univariate Analysis

* Distribution of Age, Income, Purchases

### 🔹 Bivariate Analysis

* Gender vs Purchases
* Income vs Churn

### 🔹 Multivariate Analysis

* Correlation heatmap
* Pair plots

---

## 🔧 Feature Engineering

* Created new feature:

  * `Avg_Spending = Total_Spend / Purchases`
* Converted categorical variables using one-hot encoding
* Converted target variable (`Churn`) into binary

---

## 📑 Data Profiling

Used **YData Profiling** to generate an automated report including:

* Missing values
* Statistical summary
* Correlations
* Data quality warnings

📁 Output: `report.html`

---

## 📈 Key Insights

* Customers with higher income tend to churn less
* Frequent buyers show higher retention
* Customers with long inactivity are more likely to churn
* High spending customers are more loyal

---

## 🚀 How to Run the Project

```bash
# Clone repository
git clone https://github.com/your-username/customer-churn-analysis.git

# Install dependencies
pip install pandas numpy matplotlib seaborn ydata-profiling

# Run the script
python main.py
```

---

## 📌 Project Workflow

1. Data Collection
2. Data Cleaning
3. EDA
4. Feature Engineering
5. Data Profiling
6. ML-ready Dataset

---

## 🧠 What I Learned

* Handling real-world messy data
* Working with multiple data sources
* Performing EDA and visualization
* Feature engineering techniques
* Debugging dependency issues

---

## 📎 Future Improvements

* Apply Machine Learning models
* Hyperparameter tuning
* Deploy model using Flask
* Build dashboard using Power BI

---

## ⭐ Conclusion

This project demonstrates strong skills in:

* Data preprocessing
* Data analysis
* Feature engineering
* Preparing datasets for machine learning

---

## 🙌 Author

**Your Name**
Data Analyst | Aspiring Data Scientist

---
