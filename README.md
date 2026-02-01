# A/B Testing: Marketing Campaign Optimization

Statistical analysis comparing Control vs Test marketing campaigns to drive data-driven decisions.

The goal was to determine whether the new campaign improves:

1. Click-Through Rate (CTR)

2. Conversion Rate

3. Financial performance (ROI, ROAS, CPA)

4. Overall profitability


# 🚀 A/B Testing Analysis: Marketing Campaign Optimization

## 📌 Project Overview

This project evaluates the performance of a new marketing campaign (Test variant) against the existing campaign (Control) using classical and Bayesian A/B testing methodologies.

The goal was to determine whether the new campaign improves:

* Click-Through Rate (CTR)
* Conversion Rate
* Financial performance (ROI, ROAS, CPA)
* Overall profitability

---

## 🧠 Business Problem

The marketing team launched a new ad strategy and needed to determine:

* Is the new campaign statistically better?
* Are improvements real or random noise?
* Should we roll it out company-wide?
* What is the projected financial impact?

---

## 📊 Methodology

### 1️⃣ Data Cleaning & Preparation

* Converted date columns
* Removed missing entries
* Merged datasets
* Created marketing KPIs

### 2️⃣ Key Metrics Created

* CTR
* Conversion Rate
* CPC
* CPM
* CPA
* ROAS
* ROI
* Funnel Step Conversion Rates

### 3️⃣ Statistical Testing

* Normality testing (Shapiro-Wilk)
* Variance testing (Levene’s Test)
* Independent T-Test / Mann-Whitney U
* Cohen’s d (Effect Size)
* Bonferroni Correction

### 4️⃣ Bayesian A/B Testing

* Posterior probability estimation
* Lift calculation
* Credible intervals

### 5️⃣ Financial Impact Analysis

* Profit comparison
* Annualized revenue projection


## Key Results

| Metric | Control | Test | Change | p-value | Significant |
|--------|---------|------|--------|---------|-------------|
| **Conversion Rate** | 0.546% | 0.919% | **+68.5%** | <0.001 | ✅ Yes |
| **Click-Through Rate** | 6.81% | 13.70% | **+101.0%** | <0.001 | ✅ Yes |
| **Annual Profit Impact** | - | - | **+$172,758** | - | - |

**Recommendation:** Implement Test variant with high confidence (Bayesian probability: 100%)

---

## Methodology

1. **Data Quality Assessment** - Handled missing values, validated data types
2. **Feature Engineering** - Created 13 marketing metrics (CTR, CPA, ROAS, conversion rates)
3. **Statistical Testing** - Applied t-tests/Mann-Whitney U with Bonferroni correction
4. **Bayesian Analysis** - Calculated probability of Test superiority
5. **Business Impact** - Quantified financial outcomes (ROI: $172K annually)

---

## Project Structure

```
├── data/                    
├── notebooks/              
├── outputs/                 
├── README.md
└── requirements.txt
```

---

## Technologies

**Python** | **pandas** | **NumPy** | **SciPy** | **Matplotlib** | **Seaborn** | **Jupyter**

---
