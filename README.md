

# Credit Card Customer Churn Analysis

Exploratory data analysis of a credit card customer dataset to uncover **why customers churn** and which segments are most at risk — built with Python (Pandas, NumPy, Matplotlib) and presented through two summary dashboards.

## 📌 Overview

Customer churn is one of the most expensive problems for any card issuer — it's far cheaper to retain a customer than to acquire a new one. This project analyzes a credit card customer dataset end-to-end: cleaning the raw data, answering business questions around churn drivers, and visualizing the results in an executive-style dashboard.

**Overall churn rate: 19.46%** — roughly 1 in 5 customers churned.

## 🎯 Business Questions

The analysis is organized around three themes:

**A. Customer Churn**
- What is the overall churn and retention rate?
- How does churn vary by age, gender, education, employment status, and city?

**B. Spending & Transaction Behavior**
- Does monthly spending or transaction volume correlate with churn?
- How do online and international transaction patterns affect churn?

**C. Credit Card & Financial Behavior**
- How do credit score, card type, interest rate, loans, and savings accounts relate to churn?

## 🔑 Key Findings

| Driver | Insight |
|---|---|
| **Credit Score** | Lowest scores (344–499) churn at **28.15%** vs. just **14.62%** for 800+ — the single strongest churn signal |
| **International Transactions** | Customers with 100+ international transactions churn at **30.77%**, over 3x higher than low-activity customers (19.02%) |
| **Interest Rate** | Churn rises sharply from **15.64%** (5–10%) to **25.93%** (25%+) as interest rate increases |
| **Monthly Spending** | Both very low spenders (0–1000) and very high spenders (5000+) show elevated churn, with the 5000+ group peaking at **21.38%** |
| **Card Type** | Churn is fairly consistent across Standard, Silver, Gold, and Platinum (18.9%–19.6%) — card tier alone isn't a strong differentiator |
| **Demographics** | Age, gender, and education show only minor variation (~18.9%–20.3%) — behavioral and financial factors matter far more than demographics |

**Takeaway:** Churn is driven primarily by **credit risk profile and financial stress** (low credit score, high interest rate) and by **unusual usage patterns** (heavy international transaction activity), not by demographic segments.

## Key Analysis
- Overall Customer Churn Rate
- Churn Rate by Age Group
- Churn Rate by Gender
- Churn Rate by Education
- Churn Rate by Employment Status
- Churn Rate by Monthly Spending
- Churn Rate by Credit Score
- Churn Rate by Card Type
- Churn Rate by Interest Rate


## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔄 Workflow

1. **Data Import** — loaded raw credit card customer dataset (CSV)
2. **Data Understanding** — shape, structure, summary statistics, dtypes
3. **Data Quality Checks** — missing values, duplicates, logical validation of fields (age, categorical values)
4. **Data Cleaning** — removed duplicate records, dropped low-value/irrelevant columns
5. **Data Analysis** — grouped and binned churn rate across demographic, spending, and financial variables
6. **Visualization** — built a multi-panel dashboard summarizing all key churn drivers

## 📊 Dashboards

**Dashboard 1 — Financial Behavior Drivers**
Churn rate by monthly spending, international transactions, credit score, card type, interest rate, and overall churn split.

**Dashboard 2 — Customer Demographics**
Overall churn rate, plus churn by age group, gender, education, employment status, and the monthly spending trend.

*(See dashboard images in this repository.)*


## Project Structure

Credit_Card_Churn_Analysis/
│
├── data/
├── notebooks/
├── charts/
├── reports/
├── README.md
├── requirements.txt
└── .gitignore


## 🚀 How to Run

```bash
git clone https://github.com/kumar905/<repo-name>.git
cd <repo-name>
pip install pandas numpy matplotlib seaborn
jupyter notebook Customer_Churn_Analysis.ipynb
```

## 👤 Author

**Kumar Wankhade** — Data Analyst
- 🔗 [LinkedIn]()
📧 (kumarwankhade321@gmail.com)
