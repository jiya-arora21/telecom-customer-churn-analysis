# Why Are Customers Churning?  
### An Exploratory Data Analysis with Business Insights and Retention Strategies

## Business Problem
Customer churn remains a major business challenge for subscription-based companies, as losing existing customers directly affects recurring revenue, customer lifetime value, and long-term profitability. Understanding the factors influencing customer attrition is essential for improving retention and building sustainable customer relationships.  

This project focuses on analyzing customer behavior and service-related patterns to identify the key drivers of churn and derive actionable business recommendations for improving customer retention.

---

## Objective
The primary objective of this analysis is to explore customer data to uncover patterns associated with churn behavior and identify high-risk customer segments. The project aims to transform raw customer data into meaningful business insights that can support data-driven retention strategies and improve overall business performance.

---

## Dataset Information
The analysis was performed using the Telco Customer Churn dataset, which contains customer-level information related to demographics, subscription services, payment methods, contract types, internet services, tenure, monthly charges, and churn status.  

The dataset includes both categorical and numerical variables that help analyze customer engagement, service usage behavior, and retention patterns.

---

## Project Workflow

### Data Understanding
- Explored dataset structure, feature distributions, and data types
- Reviewed categorical and numerical variables
- Analyzed unique categories and customer behavior patterns

### Data Cleaning
- Converted `TotalCharges` into a numerical format for analysis
- Identified and handled missing values
- Removed a very small number of missing observations to maintain data consistency and avoid unnecessary imputation bias
- Checked for duplicate records and validated dataset quality

### Exploratory Data Analysis
- Performed univariate, bivariate, and multivariate analysis
- Analyzed churn distribution across different customer segments
- Evaluated relationships between churn and:
  - contract type
  - payment method
  - internet service
  - tenure
  - monthly charges

### Data Visualization
Created visualizations using Matplotlib and Seaborn to identify trends, customer behavior patterns, and churn-driving factors through:
- count plots
- box plots
- histograms
- correlation heatmaps
- segmentation-based visual analysis

---

## Key Insights and Findings
- Customers with month-to-month contracts exhibited significantly higher churn compared to customers on long-term contracts.
- Electronic check users showed the highest churn rates among all payment methods, indicating lower customer engagement and retention stability.
- Fiber optic customers experienced higher churn despite being premium users, suggesting possible dissatisfaction related to pricing, service quality, or customer expectations.
- Customers with shorter tenure were more likely to churn, highlighting higher attrition risk during the early customer lifecycle stage.
- Behavioral and service-related factors were found to influence churn more strongly than demographic characteristics.

---

## Tools and Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab 

---

## Project Status
Project currently in progress.  

Further enhancements, statistical validation, and additional business-focused analysis are being incorporated to strengthen the overall analytical findings and recommendations.
