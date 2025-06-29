# 📊 Kiva Loans - Business Intelligence Project

![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)
![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Pandas](https://img.shields.io/badge/Library-pandas-yellow?logo=pandas)
![Seaborn](https://img.shields.io/badge/Visualization-seaborn-lightblue?logo=python)
![Matplotlib](https://img.shields.io/badge/Visualization-matplotlib-blue?logo=python)
![Power BI](https://img.shields.io/badge/Dashboard-Power%20BI-yellow?logo=powerbi)
![BI](https://img.shields.io/badge/Business%20Intelligence-Kiva%20Loans-green?logo=chartdotjs)

---

## 🧠 Project Description

This Business Intelligence project analyzes the **Kiva microloans dataset**, focusing on understanding patterns in loan distribution, funded amounts, and lender behavior.

The analysis was conducted using **Python, Jupyter Notebook, Power BI Dashboards**, and visualization tools, applying both descriptive statistics and correlation analysis.

---

## 📁 Project Structure

- `BI_project.ipynb` → Jupyter Notebook with full analysis  
- `masked_kiva_loans.csv` → Original (masked) dataset  
- `Presentation 2.pdf` → Final BI presentation slides  
- 🟡 **Power BI Dashboard File** (not uploaded due to size/format, but used for final visuals)

---

## 📊 Analysis Workflow

1. **Missing Values Analysis**
2. **Dropping Irrelevant Columns (`partner_id`)**
3. **Handling Nulls in Key Columns (`borrower_genders`, `lender_count`)**
4. **Feature Engineering:**
   - Extracting `borrower_count`
   - Creating `is_female` binary column
5. **Removing Duplicates**
6. **Winsorization** of extreme values (99th percentile)
7. **Converting date fields**
8. **Statistical Summary and Distributions**
9. **Correlation Analysis:**
   - Pearson & Spearman correlation between `funded_amount` and `lender_count`
10. **Visualizations:**
    - Histogram
    - Boxplot
    - Regression Plot
11. **📊 Power BI Dashboard:**
    - KPIs by region & sector
    - Time series of loan funding
    - Gender-based insights

---

## 📈 Insights

- Funded amounts and lender count are **right-skewed**
- Spearman’s correlation more robust due to non-normality
- Winsorization reduced effect of outliers
- Power BI dashboards provide interactive exploration of KPIs and demographics

---

## 🛠 Tools & Technologies

- **Python**: Data analysis
- **Jupyter Notebook**: Documentation & analysis
- **Pandas, Matplotlib, Seaborn**: Data wrangling & visualization
- **Power BI**: Dashboard design and visual exploration

---
