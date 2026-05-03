# 🏦 Bank Customer Churn Analysis
 
### Understanding why customers leave — and how to stop it

---
 
## 📌 Overview
 
Banks lose customers every day — and rarely know why.
 
This project analyzes **10,000+ customer records** to uncover the patterns behind churn: who is leaving, where, and what factors drive it. The output is a set of data-backed findings and **4 strategic business recommendations** ready to act on.
 
---
 
## 🔢 Key Numbers
 
| Metric | Value |
|--------|-------|
| Total customers analyzed | 10,000+ |
| Overall churn rate | **~20%** |
| Highest churn by country | Germany — **32.4%** |
| Highest churn by gender | Female — **25.1%** |
| Inactive member churn rate | **26.9%** vs 14.3% active |
| Churn rate — 4 products | **100%** |
 
> 1 in 5 customers leaves the bank. In Germany, nearly 1 in 3.
 
---
 
## 📊 Key Findings
 
### By Country
| Country | Churn Rate | Total Churn |
|---------|-----------|-------------|
| 🇩🇪 Germany | **32.4%** | 814 |
| 🇪🇸 Spain | 16.7% | 413 |
| 🇫🇷 France | 16.2% | 810 |
 
### By Gender
| Gender | Churn Rate | Total Churn |
|--------|-----------|-------------|
| Female | **25.1%** | 1,139 |
| Male | 16.5% | 898 |
 
### By Number of Products
| Products Owned | Churn Rate | Total Churn |
|----------------|-----------|-------------|
| 1 product | 27.7% | 1,409 |
| 2 products | **7.6%** ✅ most loyal | 348 |
| 3 products | 82.7% | 220 |
| 4 products | **100.0%** ⚠️ | 60 |
 
> Customers with 2 products are the most loyal. Beyond that, churn skyrockets — likely due to product complexity and poor experience.
 
### By Activity Status
| Status | Churn Rate | Total Churn |
|--------|-----------|-------------|
| Inactive | **26.9%** | 1,302 |
| Active | 14.3% | 735 |
 
---
 
## 🧠 Executive Summary
 
| # | Finding | Impact |
|---|---------|--------|
| 1 | Overall churn rate ~20% — 1 in 5 customers leaves the bank | 🔴 High |
| 2 | Female customers churn significantly more than male | 🟡 Medium |
| 3 | Age group 40–60 is the highest-risk segment | 🔴 High |
| 4 | Customers with 3–4 products have the highest churn rate | 🔴 High |
| 5 | Inactive members churn at nearly 2x the rate of active ones | 🔴 High |
| 6 | Churned customers tend to carry higher account balances | 🔴 High |
| 7 | Credit card ownership shows no significant effect on churn | 🟢 Low |
| 8 | Churn rate varies meaningfully across countries | 🟡 Medium |
 
---
 
## 💡 Business Recommendations
 
**1. Age-Based Retention Program**
Design loyalty programs specifically for customers aged 40–60 — wealth management services, personal financial consultation, or exclusive benefits tailored to their life stage needs.
 
**2. Early Warning System for Inactive Members**
Build an automated system that detects declining activity and proactively triggers re-engagement campaigns (promotions, financial education content, new product offers) before customers decide to leave.
 
**3. Audit the Multi-Product Customer Journey**
Review the experience of customers holding 3–4 products. The near-100% churn rate in this segment suggests friction and frustration — not loyalty — that needs to be addressed urgently.
 
**4. Segmented Approach by Gender and Country**
Deploy targeted satisfaction surveys for female customers and investigate country-level churn gaps, particularly Germany, to identify service weaknesses in each market.
 
---
 
## 🗂️ Project Structure
 
```
bank-customer-churn-analysis/
│
├── data/
│   └── data.csv                   # Cleaned data output
│
├── notebooks/
│   └── Bank_Customer_Churn_Analysis.ipynb  # Executive summary & recommendations
│
└──  outputs/
    └── figures/                     # Exported charts

```
 
---
 
## 🚀 Getting Started
 
```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/bank-customer-churn-analysis.git
cd bank-customer-churn-analysis
 
# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows
 
# 3. Install dependencies
pip install -r requirements.txt
 
# 4. Launch Jupyter Notebook
jupyter notebook
```
 
## 👩‍💻 Author
 
**Neng Intan Nuraeini** — Data Analyst & Web Developer, Bandung 🇮🇩
 

 
