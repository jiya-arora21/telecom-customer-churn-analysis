# Why Are Customers Churning?

### An Exploratory Data Analysis with Business Insights and Retention Strategies

---

## The Business Story

Customer churn is one of the most pressing challenges faced by subscription-based businesses, particularly in the telecom industry where customers can easily switch providers. Losing customers affects not only **recurring revenue**, but also **customer lifetime value, acquisition costs, and long-term profitability**.

For telecom companies, retaining customers is often more cost-effective than acquiring new ones. However, customer attrition is rarely random — it is often influenced by behavioral patterns, service experience, pricing, and engagement levels.

This project was designed to answer one critical business question:

> **Why do customers churn, and what actions can businesses take to reduce customer attrition?**

Using customer-level telecom data, this analysis explores churn behavior to identify **high-risk customer segments**, uncover hidden churn patterns, and recommend **data-driven retention strategies**.

---

## Project Objective

The objective of this project is to analyze customer churn behavior and identify the key factors influencing customer retention.

The analysis aims to:

* Identify **customers at high risk of churn**
* Understand how **service usage and customer behavior** influence retention
* Analyze the impact of **contracts, payment methods, internet services, pricing, and tenure**
* Validate observed patterns through **statistical testing**
* Generate **business recommendations** to improve retention and reduce churn

---

## Dataset Overview

The analysis uses the **Telco Customer Churn Dataset**, which contains customer-level information related to:

* Customer demographics
* Subscription services
* Internet service categories
* Contract types
* Payment methods
* Monthly charges and tenure
* Customer churn status

The dataset consists of both **categorical and numerical variables**, enabling behavioral analysis, customer segmentation, and statistical evaluation of churn patterns.

---

# The Analytical Journey

Rather than directly jumping into conclusions, the analysis followed a structured process to understand customer behavior and validate churn patterns systematically.

### 1. Understanding the Data

The project began with an initial exploration of the dataset to understand:

* Dataset structure and feature composition
* Variable types and customer attributes
* Churn distribution and class balance
* Customer behavior patterns across services

This stage helped establish business context and identify relevant variables for deeper analysis.

---

### 2. Data Cleaning & Preparation

Before performing analysis, the dataset was cleaned to ensure consistency and analytical reliability.

The preprocessing process included:

* Converting `TotalCharges` into numerical format
* Identifying missing values
* Removing a small number of incomplete observations
* Checking for duplicate records
* Validating overall data quality

This ensured that subsequent findings were based on reliable and interpretable data.

---

### 3. Exploratory Data Analysis (EDA)

Once the dataset was prepared, exploratory analysis was performed to uncover customer behavior patterns associated with churn.

#### Univariate Analysis

Initial analysis focused on understanding the distribution of important variables, including:

* Churn distribution
* Contract type
* Payment methods
* Internet services
* Monthly charges
* Customer tenure

This provided an overview of customer composition and service behavior.

#### Bivariate Analysis

To understand churn drivers, relationships between customer churn and business variables were analyzed:

* **Contract Type vs Churn**
* **Payment Method vs Churn**
* **Internet Service vs Churn**
* **Monthly Charges vs Churn**
* **Tenure vs Churn**
* **Senior Citizen Status vs Churn**

This stage helped identify potential churn indicators and vulnerable customer groups.

#### Multivariate Analysis

To move beyond isolated relationships, multivariate analysis was performed to understand how combinations of variables influenced churn behavior.

The analysis included:

* **Contract Type × Payment Method × Churn**
* **Internet Service × Contract Type × Churn**

This helped identify customer segments with compounded churn risk rather than relying on single-factor explanations.

---

### 4. Visual Exploration

To better interpret customer behavior patterns, multiple visualizations were created using **Matplotlib** and **Seaborn**.

Visual analysis included:

* Count plots
* Histograms
* Box plots
* Comparative churn visualizations
* Correlation heatmaps
* Segmentation-based analysis

These visualizations helped transform complex customer behavior into intuitive business insights.

---

# Statistical Validation

While exploratory analysis reveals patterns, statistical testing helps determine whether those patterns are **meaningful or simply random observations**.

To validate findings, inferential statistical methods were applied.

### Confidence Interval Analysis

A **95% confidence interval** was calculated to estimate the likely range of the actual churn rate in the customer population.

This provided a statistically reliable estimate of customer attrition and strengthened confidence in churn measurement.

### Margin of Error Analysis

A **margin of error analysis** was performed to evaluate the precision of churn estimates and assess reliability.

This helped quantify uncertainty around churn estimation.

### Z-Test for Proportion Comparison

To determine whether differences in churn behavior across customer groups were statistically significant, **Z-tests** were conducted for:

* **Senior Citizens vs Non-Senior Citizens**
* **High Monthly Charges vs Low Monthly Charges**

These tests validated whether churn differences across groups were statistically meaningful.

### Chi-Square Test of Association

To evaluate whether customer churn was significantly associated with service and behavioral variables, **Chi-Square Tests** were performed for:

* **Contract Type vs Churn**
* **Payment Method vs Churn**
* **Internet Service vs Churn**

The statistical results confirmed strong relationships between churn behavior and service-related factors.

---

# Key Business Insights

The analysis revealed several meaningful churn patterns:

### High-Risk Customer Segments

Customers belonging to the following groups exhibited the highest churn risk:

* **Month-to-month contract customers**
* **Electronic check users**
* **Fiber optic internet users**
* **Customers with shorter tenure**
* **Customers with higher monthly charges**

### Major Findings

* Customers on **month-to-month contracts** churn significantly more than long-term contract customers.
* **Electronic check users** demonstrate higher churn compared to customers using automatic payment methods.
* **Fiber optic customers**, despite being premium users, exhibit elevated churn risk, suggesting possible dissatisfaction related to pricing, service quality, or customer expectations.
* Customers with **short tenure** are significantly more vulnerable during the early stages of the customer lifecycle.
* **Behavioral and service-related factors** influence churn more strongly than demographic characteristics.

---

# Strategic Business Recommendations

Based on the findings, several targeted retention strategies were identified:

### Strengthen Long-Term Contract Adoption

Encourage customers to transition toward **yearly and long-term contracts** through discounts, loyalty incentives, and bundled offers.

### Improve Fiber Optic Customer Retention

Improve **service quality, customer support, and targeted engagement strategies** for premium fiber optic users.

### Promote Automatic Payment Methods

Encourage customers to adopt **automatic payment systems** to reduce payment friction and improve retention.

### Monitor High-Risk Customer Segments

Proactively identify and monitor customers at high churn risk through behavioral indicators.

### Strengthen Early Customer Engagement

Improve onboarding, early support, and customer engagement during the **first stages of the customer lifecycle**.

### Optimize Pricing for High-Charge Customers

Introduce **flexible pricing models and personalized offers** for price-sensitive customers.

### Develop Personalized Retention Strategies

Adopt **segment-specific retention approaches** rather than one-size-fits-all customer retention efforts.

---

# Business Impact

This project demonstrates how **exploratory analytics combined with statistical validation** can help businesses better understand customer churn and make informed retention decisions.

By implementing targeted, data-driven strategies, telecom companies can:

* Reduce customer attrition
* Improve customer retention
* Increase customer lifetime value
* Strengthen customer loyalty
* Stabilize recurring revenue
* Improve long-term profitability

---

## Tools & Technologies Used

### Programming & Analysis

* Python
* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Statistical Analysis

* Statsmodels
* SciPy

### Development Environment

* Google Colab

---

## Project Status

**Completed — End-to-End Exploratory, Statistical, and Business-Focused Churn Analysis**
