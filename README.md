# Customer Churn Analysis (Telecom)

## 📌 Project Overview

Customer churn is a critical problem in the telecommunications industry, as acquiring new customers is significantly more expensive than retaining existing ones. This project focuses on analyzing customer-level data from a telecom company to understand patterns and factors that contribute to customer churn.

The goal of this analysis is to gain insights that can help the company design better customer retention strategies.

---

## 🎯 Business Problem

The company wants to:

* Understand **why customers leave (churn)** or switch to another provider
* Identify **which customers are more likely to churn**
* Support decision-making for **customer retention strategies**, such as targeted promotions, discounts, or service improvements

---

## 📊 Dataset Information

* **Source**: Kaggle – Telecom Customer Churn Dataset
* **Rows**: 3,333 customers
* **Columns**: 11 features
* **Target Variable**: `churn`

The dataset contains customer-level information related to:

* Call usage
* Customer service interactions
* Subscription plans (e.g., data plan)
* Churn status

---

## 🔍 Initial Data Understanding

Key findings from early exploration:

* No missing values were found in the dataset
* Most customers contacted customer service **1–2 times**, but a few contacted up to **9 times**
* Only **27% of customers** subscribed to a data plan, indicating that the dataset reflects an older telecom usage pattern
* The overall churn rate is **14.49%**, which means approximately 1 in 7 customers churned

---

## 🧪 Analysis Scope

This project focuses on:

* Exploratory Data Analysis (EDA)
* Descriptive statistics
* Identifying patterns related to customer churn

⚠️ **Note**: This project does **not** include predictive modeling. The emphasis is on understanding data patterns and business insights.

---

## 🛠️ Tools & Technologies

* Python
* Jupyter Notebook
* pandas
* numpy
* matplotlib / seaborn (for visualization)

---

## 📁 Project Structure

```
customer-churn-analysis/
│
├── customerChurnAnalysis.ipynb
├── README.md
├── data/
│   └── telecom_churn.csv
├── .gitignore
```

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/customer-churn-analysis.git
   ```
2. Navigate to the project directory
3. Open the notebook:

   ```bash
   jupyter notebook customerChurnAnalysis.ipynb
   ```

---

## 📌 Future Improvements

* Feature engineering for churn-related behavior
* Customer segmentation analysis
* Churn prediction modeling using machine learning

---

## 👤 Author

**Yulita Rahma**
Data Analyst Enthusiast

---

✨ This project is part of a personal data analytics portfolio and is intended for learning and demonstration purposes.
