# Loan Application Risk Analysis

This project analyzes financial and demographic attributes of loan applicants to identify patterns associated with loan default. It focuses on exploratory data analysis (EDA), feature profiling, and insight-driven reporting for financial risk assessment.

---

## 📊 Project Objectives

- Understand the distribution of applicant income, education, and credit history
- Identify key indicators that differentiate defaulting from non-defaulting applicants
- Create visualizations that highlight income-based risk patterns
- Support future development of risk-scoring models or lending policies

---

## 🧠 Techniques Used

- Data cleaning and preprocessing (missing value treatment, filtering)
- Univariate and bivariate EDA using boxplots, KDE, and categorical segmentation
- Comparison of repayment status against applicant income and loan details
- Summary insights translated into business-facing visuals

---

## 🛠️ Tools & Libraries

- Python (pandas, numpy, seaborn, matplotlib)
- Jupyter Notebook for interactive analysis
- Visuals export-ready for offline portfolio inclusion

---

## 📂 Dataset Source

The dataset is sourced from Kaggle and contains over 300,000 anonymized loan applications from a real lending institution:

```python
import kagglehub

# Download latest version
path = kagglehub.dataset_download("dssouvikganguly/application-datacsv")

print("Path to dataset files:", path)
