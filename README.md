# 🧼 Customer Personality Analysis - Data Cleaning Task

This repository contains a cleaned version of the **Customer Personality Analysis** dataset, originally obtained from Kaggle. The goal of this task is to demonstrate essential data cleaning and preprocessing skills using Excel/Python (Pandas).

## 🧠 Objective

Clean and prepare a raw dataset that includes:
- Null values
- Duplicates
- Inconsistent text formats
- Mixed data types
- Unclean column headers

## 🛠 Tools Used
- Excel (conceptually)
- Python with Pandas (for execution)

---

## 🔍 Dataset Overview

The original dataset includes customer details such as:
- Demographics: Age, Marital Status, Education
- Spending habits across categories (Wine, Fruits, etc.)
- Responses to marketing campaigns
- Customer joining date

---

## ✨ Data Cleaning Summary

| Task                          | Description |
|-------------------------------|-------------|
| ✅ Missing Values             | Detected 24 missing entries in the `Income` column. |
| ✅ Duplicates                 | Checked using `.drop_duplicates()` — none found. |
| ✅ Standardized Text Values   | Cleaned `Education` and `Marital_Status` columns using `.str.title()`. |
| ✅ Date Format Fix            | `Dt_Customer` converted to datetime format (`dd-mm-yyyy`). |
| ✅ Column Header Cleaning     | All headers converted to lowercase with underscores. |
| ✅ Data Type Fix              | Ensured numeric and date columns have appropriate types. |

---

## 📁 Files Included

- `marketing_campaign_cleaned.csv`: The final cleaned dataset (ready for analysis)
- `README.md`: This documentation

---

## 🧪 Sample Insights to Explore

- Age distribution of customers
- Campaign success rates
- Spending behavior by education or marital status
- Income vs. Recency of purchases

---

## ✅ How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/customer-personality-cleaning.git
