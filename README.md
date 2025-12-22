# Customer Churn Analysis - Telecom Company

## 📌 Project Overview
Customer churn is a major challenge in the telecommunication industry, where retaining existing customers is more cost-effective than acquiring new ones.  
This project aims to analyze customer behavior and identify key factors that contribute to customer churn using exploratory data analysis (EDA).

## 🎯 Business Problem
The company wants to understand:
- What factors are associated with customer churn?
- Which customers are more likely to churn?
- What actionable insights can help reduce churn?

## 📊 Dataset
- Source: Kaggle – Telecom Customer Churn Dataset
- Total records: 3,333 customers
- Target variable: `Churn` (1 = churn, 0 = not churn)

## 🔍 Analysis Approach
The analysis focuses on:
- Data understanding & cleaning
- Exploratory Data Analysis (EDA)
- Customer behavior analysis related to churn
- Business-driven insights and recommendations

Key variables explored:
- Customer Service Calls
- Data Plan subscription
- Monthly Charges
- Overage Fees

## 💡 Key Insights
- Customers who contacted customer service more frequently showed a significantly higher churn rate.
- Customers without a data plan had nearly double the churn rate compared to those with a data plan.
- Financial factors such as monthly charges showed weak linear correlation with churn.
- Service-related factors (customer service calls) were more influential than cost-related factors.

## 🧠 Business Interpretation
The results suggest that churn is more strongly driven by customer dissatisfaction with service rather than pricing.  
Customers are willing to pay higher fees as long as the service quality meets expectations.

## 📈 Business Recommendations
- Improve customer service quality and reduce unresolved issues.
- Identify customers with frequent customer service calls as high-risk churn segments.
- Encourage data plan adoption to increase customer retention.
- Proactively engage high-risk customers before they decide to leave.

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

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
2. Install required Python libraries
3. Open `customerChurnAnalysis.ipynb`
4. Run the notebook sequentially

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
