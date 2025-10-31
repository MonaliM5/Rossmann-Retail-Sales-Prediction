# 🏪 Rossmann Retail Sales Prediction

A business-focused regression project to forecast sales in Rossmann retail stores using real-world data and machine learning.

---

## 📊 **Project Overview**
This project analyzes daily sales data from 1,115 Rossmann stores across Europe.  
Through **data wrangling, feature engineering, and exploratory data analysis (EDA)**, it identifies key business factors influencing store performance and provides insights for strategic sales forecasting.

---

## 🧹 **Data Wrangling Summary**
- Merged sales and store datasets using the common key **Store**.
- Handled missing values, fixed unrealistic entries, and added missing-value flags.
- Engineered new features:
  - `CompetitionOpenMonths`
  - `IsPromo2Active`
  - `SalesPerCustomer`
  - `ZeroSalesWhileOpen`
- Treated outliers in `CompetitionDistance` and standardized data types.

---

## 📈 **Key Insights**
- Long-standing competition is linked to more stable sales.
- Promotional activity follows seasonal patterns.
- Some open days had zero sales, indicating unproductive periods.
- `SalesPerCustomer` revealed variation in spending by store type and assortment.

---

## 🧠 **Tech Stack**
- **Python:** pandas, numpy, matplotlib, seaborn  
- **Environment:** Google Colab  
- **Version Control:** Git & GitHub  

---

## 📁 **Repository Structure**
Rossmann-Retail-Sales-Prediction/ │ ├── Rossmann-Retail-Sales-Prediction.ipynb     # Main project notebook ├── data/                                      # Datasets ├── outputs/                                   # Charts, reports, and processed data ├── utils/                                     # Optional helper scripts ├── README.md                                  # Project documentation ├── requirements.txt                           # Python dependencies └── .gitignore                                 # Files to ignore in Git


---

## 🚀 **Next Steps**
- Complete univariate, bivariate, and multivariate analysis.  
- Develop predictive models for store-level sales forecasting.  
- Interpret insights for strategic business decisions.

---
