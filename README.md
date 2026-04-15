# ecommerce-customer-analytics-platform
End-to-end data analytics project analyzing customer behavior, retention, RFM segmentation, cohort trends, and A/B testing for an e-commerce platform.
# 🛒 E-Commerce Customer Analytics Platform

##  Project Overview

This project analyzes customer behavior for an e-commerce platform to understand the decline in repeat purchases and identify opportunities to improve retention and revenue.

The analysis is performed on real-world messy datasets and covers end-to-end data analytics including ETL, segmentation, cohort analysis, and A/B testing.

---

## Objectives

* Understand why repeat purchase rates are declining
* Identify high-value customer segments
* Evaluate recommendation system performance
* Provide actionable business insights

---

##  Datasets Used

* **Customers** (150K rows) → user details & acquisition info
* **Transactions** (800K rows) → purchase behavior
* **Products** (5K rows) → product catalog
* **Recommendation Exposure** (400K rows) → A/B testing data

---

## ⚙️ Tech Stack

* **SQL** → Data cleaning, aggregation, analysis
* **Python (Pandas, NumPy)** → Data processing
* **Matplotlib / Seaborn** → Visualization
* **Jupyter Notebook / Google Colab** → Analysis workflow

---

## 🔧 Key Steps Performed

### 1. Data Cleaning & ETL

* Removed invalid transactions (negative values, failed payments)
* Standardized categorical variables (channels, countries)
* Handled missing and inconsistent data

### 2. Customer Master Table

* Created customer-level metrics:

  * Total transactions
  * Total revenue
  * Average order value
  * Recency & lifetime

### 3. RFM Segmentation

* Segmented customers into:

  * Champions
  * Loyal Customers
  * Potential Loyalists
  * At Risk
  * Lost

### 4. Cohort Analysis

* Built monthly cohorts
* Measured retention trends over time
* Identified sharp drop after first purchase

### 5. A/B Testing

* Evaluated recommendation algorithms using:

  * CTR (Click-through rate)
  * Conversion rate
  * Revenue impact
* Found **Recently Viewed** performs best

---

##  Key Insights

* Most customers **do not return after first purchase**
* Revenue is driven mainly by **Champions segment**
* Customers typically buy **only 1 item per order**
* **Recently viewed recommendations** perform best
* Revenue varies significantly across **channels and countries**

---

##  Business Recommendations

* Improve retention using **email reminders & loyalty programs**
* Focus on **high-value customers (Champions)**
* Prioritize **recently viewed recommendations**
* Increase cart size using **cross-sell & bundle offers**
* Optimize marketing spend on **high-performing channels**

---

## Project Structure

```
submission/
├── README.md
├── sql/
│   ├── 01_data_cleaning.sql
│   ├── 02_customer_master.sql
│   ├── 03_rfm_segmentation.sql
│   ├── 04_cohort_analysis.sql
│   └── 05_ab_test_analysis.sql
├── notebooks/
│   ├── analysis.ipynb
│   └── statistical_tests.ipynb
├── visualizations/
│   └── plots/
└── data/
    └── customer_master.csv
```

---

##  How to Run

1. Clone the repository
2. Load datasets into your environment
3. Run SQL scripts in order
4. Execute Jupyter Notebook for analysis & visualization

---

## Time Spent

* Data Cleaning: 25%
* Analysis (RFM, Cohort, A/B): 50%
* Insights & Reporting: 25%

---

##  Conclusion

The business is currently facing **low retention and dependency on a small group of high-value customers**. Improving personalization, retention strategies, and acquisition quality can significantly boost long-term growth.

---

## ⭐ Author

**Umesh Chandra**
Data Science & Machine Learning Enthusiast
