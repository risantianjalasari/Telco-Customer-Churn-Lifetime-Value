# Telco-Customer-Churn-Lifetime-Value
**Overview**
Customer retention is one of the biggest challenges in the telecommunications industry. Losing existing customers not only reduces recurring revenue but also increases the cost of acquiring new ones.

This project explores customer churn using the IBM Telco Customer Churn dataset and follows a complete Business Intelligence workflow—from data preparation and exploratory analysis to business recommendations and an executive dashboard.

Rather than focusing only on visualizations, the project aims to answer practical business questions, identify customers with the highest churn risk, estimate potential revenue at risk, and provide recommendations that support better decision-making.

**Business Problem**
The company has experienced a considerable number of customers leaving its services. However, the business does not clearly understand:
- Which customers are most likely to churn
- What factors contribute to customer churn
- Which customer segments generate the highest revenue
- Which customers should be prioritized for retention efforts
Without these insights, retention strategies may not be targeted effectively, resulting in unnecessary revenue loss.

**Project Objectives**
This analysis was conducted to:
- Measure the overall customer churn rate
- Identify customer segments with the highest churn risk
- Understand how customer characteristics and subscribed services influence churn
- Evaluate customer value using revenue and estimated Customer Lifetime Value (CLV)
- Estimate potential revenue at risk
- Develop an interactive dashboard to support business decisions

**Dataset**
Source : IBM Sample Dataset — Telco Customer Churn
Records : 7,043 customers
Features :
- 21 original variables covering:
- Customer demographics
- Account information
- Internet and phone services
- Billing information
- Customer churn status

**Project Workflow**
Business Understanding
        ↓
Data Quality Assessment
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Exploratory Data Analysis
        ↓
Business Impact Analysis
        ↓
Business Recommendations
        ↓
SQL Analysis
        ↓
Looker Studio Dashboard

**Tools**
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- SQL
- Google Sheets
- Looker Studio

## Project Highlights
✔ End-to-end Business Intelligence project
✔ Data quality assessment and cleaning
✔ Feature engineering for customer segmentation
✔ Exploratory analysis driven by business questions
✔ Business impact analysis, including revenue at risk
✔ Interactive executive dashboard in Looker Studio
✔ Actionable recommendations for customer retention

**Data Preparation**
The dataset was reviewed before analysis to ensure data quality. The preparation process included:
- Checking data types
- Identifying missing values
- Detecting blank values
- Removing invalid records
- Feature engineering
- Creating analytical datasets

Additional features created during the analysis include:
- Customer Lifetime Value (Estimated)
- Tenure Group
- Total Services
- Risk Segment

**Key Business Questions**
The analysis focuses on answering the following questions:
1. What is the overall customer churn rate?
2. Which customer segments experience the highest churn?
3. How does contract type influence customer retention?
4. Does customer tenure affect churn?
5. Which internet services are associated with higher churn?
6. Does payment method influence customer churn?
7. Which customer segments contribute the highest revenue?
8. How much recurring revenue is potentially at risk due to customer churn?

**Key Findings**
The analysis identified several important patterns.
- Customers with month-to-month contracts are significantly more likely to churn than customers with longer-term contracts.
- Early-tenure customers represent the highest-risk customer group.
- Customers subscribing to additional services such as Tech Support and Online Security generally demonstrate better retention.
- Customer churn is concentrated within specific customer segments rather than being evenly distributed across the customer base.
- A substantial portion of recurring monthly revenue is associated with customers who eventually churn, highlighting the financial impact of customer retention.

**Business Recommendations**
Based on the findings, several initiatives could help improve customer retention.
- Encourage customers to migrate from month-to-month contracts to annual subscriptions.
- Strengthen onboarding programs during the first year of the customer lifecycle.
- Promote bundled services that include Tech Support and Online Security.
- Prioritize retention campaigns for customers with high estimated lifetime value.
- Monitor customer segments with elevated churn risk through an executive dashboard.

**Dashboard**
The interactive dashboard was built in Looker Studio and consists of four pages:
Executive Overview
Customer Profile
Revenue Analysis
Customer Churn Analysis
The dashboard enables business users to monitor customer performance and identify high-risk customer segments without requiring technical knowledge.
(on progress dashboard)

**Repository Structure**
telco-customer-churn-analysis/

│
├── data/
│     raw/
│     processed/
│
├── notebooks/
│     Telco_Customer_Churn_Analysis.ipynb
│
├── sql/
│     churn_analysis.sql
│
├── dashboard/
│     dashboard_preview.png
│
├── presentation/
│     Executive_Summary.pdf
│
└── README.md

**What I Learned**
One of the most interesting parts of this project was moving beyond descriptive analysis.

Instead of stopping at identifying who churned, I explored how customer characteristics, service adoption, and contract types relate to retention and business value. Estimating revenue at risk and segmenting customers based on risk helped connect the analysis to practical business decisions rather than simply reporting statistics.

This project also reinforced the importance of presenting technical analysis in a way that business stakeholders can easily understand and use.

**Contact**
Risanti Anjalasari
LinkedIn : [https://www.linkedin.com/in/risanti-anjalasari-aa2a96a2/]
GitHub   : [https://github.com/risantianjalasari]
Email    : risantianjalasari@gmail.com
Visualization : [https://datastudio.google.com/reporting/a0384232-2bf9-4423-a7b7-4eeaada80b83]
