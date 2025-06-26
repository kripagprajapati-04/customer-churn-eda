# Customer Churn EDA 📊

This is my first-ever data analysis project! I explored a customer churn dataset to understand which types of customers are most likely to leave a telecom company. The goal was to practice cleaning, analyzing, and visualizing data using Python.

## 🔧 Tools Used:
- Python (Jupyter Notebook)
- Pandas, NumPy
- Matplotlib

## 📁 Dataset:
- Telco Customer Churn (21 columns, 7403 rows)
- Contains info like customer gender, contract type, tenure, monthly charges, and whether they churned

## 🧼 Data Cleaning:
- Fixed `TotalCharges` column (was wrongly stored as object)
- Removed null values (less than 10)
- Confirmed dataset is clean and ready

## 📊 Analysis Highlights:

- 🔁 **Contract Type vs Churn**: Month-to-month customers are more likely to churn
- 🧍‍♀️ **Gender vs Churn**: No significant difference in churn rate by gender
- 💸 **Monthly Charges vs Churn**: Customers who churned paid slightly less
- ⏳ **Tenure vs Churn**: New customers churn more, long-term customers tend to stay

## 📌 Key Takeaway:
> Most churn came from new, lower-paying customers on short-term contracts. Telcos should improve onboarding and add value to lower-tier plans.

---

This project helped me build confidence in data cleaning, grouping, and storytelling using graphs. I'm excited to keep learning and start my next project soon!
