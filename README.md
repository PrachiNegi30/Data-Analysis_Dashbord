# OTT Subscription Churn Analysis

An end-to-end data analytics project that analyzes customer churn for an OTT subscription platform. The project integrates customer, subscription, and support data to identify churn patterns, measure business impact, and provide actionable recommendations for improving customer retention.

## Project Overview

Customer retention is one of the most important success factors for subscription-based businesses. This project focuses on identifying customers with a high likelihood of churn by combining customer demographics, subscription details, and support interaction data.

The analysis includes data cleaning, feature engineering, exploratory data analysis (EDA), KPI generation, and visualization to help stakeholders understand customer behavior and reduce revenue loss.

## 🎯 Objectives

- Measure customer churn and retention rates.
- Identify high-risk customer segments.
- Analyze churn across subscription plans and contract types.
- Measure the revenue impact of customer attrition.
- Recommend strategies to improve customer retention.

---

## Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **SQLite / SQL**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

# Dataset

The analysis combines data from three relational tables:

### Customer
- Customer ID
- Name
- Gender
- Date of Birth
- Country
- State
- Interests

### Subscription
- Subscription Start Date
- Subscription Type
- Plan Type
- Contract Type
- Renewal Date
- Cancellation Date
- Monthly Charges
- Customer Lifetime Value (CLTV)
- Churn Score

### Support
- Complaint Date
- Escalation Count
- CSAT Score
- Customer Comments

---

# Project Workflow

### 1. Data Extraction

- Connected Python with a SQL database.
- Imported customer, subscription, and support datasets.
- Combined multiple relational tables for analysis.

---

### 2. Data Cleaning

- Removed duplicate records.
- Handled missing values.
- Corrected data types.
- Renamed columns.
- Performed quality checks.

---

### 3. Feature Engineering

- Calculated customer tenure.
- Created churn indicators.
- Generated new business metrics.
- Prepared analytical features for reporting.

---

### 4. Exploratory Data Analysis

Performed analysis using:

- GroupBy
- Aggregations
- Pivot Tables
- Statistical summaries

---

### 5. Data Visualization

Created visualizations to analyze:

- Churn distribution
- Subscription plans
- State-wise churn
- Revenue trends
- Customer segmentation

---

# Key Performance Indicators (KPIs)

The project calculates more than **20 business KPIs**, including:

- Overall Churn Rate
- Retention Rate
- Churn by Plan Type
- Churn by State
- Average Revenue Per User (ARPU)
- Average Customer Tenure
- Revenue at Risk
- Customer Lifetime Value (CLTV)
- Escalation Rate
- Average Complaints per Customer

---

# Key Insights

- Overall customer churn rate: **28.6%**
- Customer retention rate: **71.4%**
- Monthly contract customers showed significantly higher churn than annual contract customers.
- Most customer churn occurred during **September 2024**.
- Karnataka recorded the highest churn among all states.
- Basic subscription plans accounted for the largest share of churn.
- Average customer tenure: **1,451 days**
- Average Revenue Per User (ARPU): **₹18.8**
- Estimated revenue loss due to churn: **₹74**
- Estimated Customer Lifetime Value (CLTV) loss: **₹2,047**
- Revenue loss due to churn represented approximately **18%** of total revenue.

---

# Business Recommendations

Based on the analysis:

- Encourage customers to migrate from monthly to annual subscription plans.
- Investigate the increase in churn during September 2024.
- Analyze customer complaints and service issues in Karnataka.
- Prioritize customers with high churn scores for retention campaigns.
- Monitor pricing changes and competitor activity.
- Improve customer support response and complaint resolution.

---

# Business Impact

The project demonstrates how customer data from multiple sources can be transformed into meaningful business insights.

Key outcomes include:

- Built an end-to-end churn analytics pipeline.
- Integrated multiple relational datasets for customer analysis.
- Generated 20+ business KPIs.
- Identified customer segments with the highest churn risk.
- Quantified revenue loss and CLTV erosion caused by churn.
- Produced actionable recommendations to improve customer retention.

---

# Project Structure

```
OTT-Churn-Analysis
│
├── data/
│   ├── customer.csv
│   ├── subscription.csv
│   └── support.csv
│
├── notebooks/
│   └── churn_analysis.ipynb
│
├── sql/
│   └── queries.sql
│
├── dashboard/
│   └── churn_dashboard.pbix
│
├── images/
│
├── README.md
└── requirements.txt
```

---

# Future Improvements

- Develop a machine learning model for churn prediction.
- Build an interactive dashboard using Streamlit.
- Automate data refresh and reporting.
- Perform cohort and retention analysis.
- Deploy the project for real-time business monitoring.

---

## 📬 Contact

**Your Name**

- LinkedIn: https://linkedin.com/in/your-profile
- GitHub: https://github.com/your-username
