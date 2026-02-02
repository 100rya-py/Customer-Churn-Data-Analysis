# 📊 Customer Churn Analysis Project

## 👋 About This Project
Welcome to my Customer Churn Analysis project! In this project, I analyzed a dataset of telecom customers to understand **why customers leave (churn)** and **what strategies can be used to retain them**.

Using Python and data visualization libraries, I cleaned the raw data, explored key patterns, and derived actionable insights to help the business reduce attrition.

---

## 🛠️ Tech Stack & Tools
* **Python:** Core programming language.
* **Pandas:** For data cleaning and manipulation.
* **Seaborn & Matplotlib:** For creating visualizations.
* **Jupyter Notebook:** The interactive environment used for analysis.

---

## 🧹 Data Cleaning & Transformation
Before analyzing, I performed the following steps to ensure data quality:
* **Standardization:** Converted all column names to lowercase for consistency.
* **Encoding:** Transformed the `SeniorCitizen` column from binary (0/1) to categorical (No/Yes) for better readability.
* **Handling Nulls:** Identified blank values in `TotalCharges` (for new customers with 0 tenure) and replaced them with `0`, converting the column to float.

---

## 🔍 Key Findings & Insights

### 📉 1. Overall Churn
* Approximately **26.54%** of the total customer base has churned.

### 👥 2. Demographics
* **Gender:** Churn rates are nearly identical between males and females, meaning gender is not a key driver.
* **Senior Citizens:** Older customers (Senior Citizens) have a higher churn rate compared to younger customers.

### 📝 3. Contract & Tenure (Major Drivers)
* **Contract Type:** Customers on **Month-to-Month** contracts have the highest churn rate. Those on One-Year or Two-Year contracts are significantly more stable.
* **Tenure:** New customers (short tenure) are at the highest risk of leaving. Loyalty increases significantly as tenure increases.

### 💳 4. Payment & Services
* **Payment Method:** The **Electronic Check** payment method is associated with the highest churn. Automatic payments (Credit Card, Bank Transfer) show the lowest churn.
* **Support Services:** Customers who do **not** have Online Security or Tech Support are much more likely to churn.

---

## 🚀 Strategic Recommendations
Based on the data, the following actions are recommended to reduce churn:
1.  **Incentivize Long-Term Contracts:** Move month-to-month users to 1 or 2-year plans.
2.  **Promote Auto-Pay:** Encourage users to switch from Electronic Checks to automatic payment methods.
3.  **Bundle Support Services:** Offer Tech Support and Online Security as part of standard bundles to increase retention.

---

## 📷 Visualizations
Please check the `Customer Churn Data Analysis.ipynb` file to see the complete code and interactive plots generated during this analysis, for summary check out the Presentation file.
