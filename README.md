# 📊 Customer Churn Analysis & Prediction

An end-to-end Data Analytics and Machine Learning project designed to analyze customer churn behavior, uncover key retention drivers, and predict customers at risk of leaving. The solution combines SQL-based ETL processes, interactive Power BI dashboards, and predictive Machine Learning models to enable data-driven business decisions and proactive customer retention strategies.

---

## 🎯 Business Problem

Customer churn is one of the most critical challenges for subscription-based and service-oriented businesses. Losing existing customers directly impacts revenue, acquisition costs, and long-term growth.

This project aims to:

* Identify the primary factors contributing to customer churn.
* Analyze churn trends across demographic, geographic, and service dimensions.
* Predict high-risk customers before they churn.
* Support targeted retention campaigns through actionable insights.

---

## 🛠️ Tech Stack

| Technology                          | Purpose                                      |
| ----------------------------------- | -------------------------------------------- |
| Microsoft SQL Server                | ETL Pipeline, Data Cleaning & Transformation |
| SQL Server Management Studio (SSMS) | Database Management                          |
| Power BI                            | Data Modeling & Interactive Dashboards       |
| Python                              | Machine Learning Development                 |
| Scikit-learn                        | Predictive Modeling (Random Forest)          |
| Pandas & NumPy                      | Data Processing & Analysis                   |

---

## 🔄 Project Workflow

### 1️⃣ Data Extraction, Transformation & Loading (ETL)

* Imported raw customer datasets into SQL Server staging tables.
* Performed data cleaning, validation, and transformation.
* Handled missing values and standardized categorical fields.
* Created production-ready tables and analytical SQL views for reporting.

### 2️⃣ Data Modeling & Visualization

Developed an interactive Power BI dashboard featuring:

* Customer Segmentation Analysis
* Churn Trend Monitoring
* Service Usage Insights
* Geographic Churn Distribution
* Executive KPI Overview

#### Key DAX Measures

* Total Customers
* Churned Customers
* Churn Rate (%)
* New Customer Acquisition
* Customer Retention Metrics

#### Custom Calculated Columns

* Churn Flag
* Age Group Classification
* Tenure Group Segmentation
* Risk Categorization

---

### 3️⃣ Machine Learning Prediction

Built a predictive churn model to identify customers likely to leave.

#### Model Development

* Encoded categorical features using Label Encoding.
* Performed train-test split (80/20).
* Trained a Random Forest Classifier.
* Evaluated model performance using:

  * Confusion Matrix
  * Classification Report
  * Accuracy Metrics

#### Prediction Outcome

* Classified customers based on churn probability.
* Generated actionable churn-risk predictions.
* Enabled proactive customer retention planning.

---

## 📈 Dashboard Highlights

### Executive KPI Dashboard

* Total Customers
* Total Churned Customers
* Churn Rate (%)
* New Customer Joiners

### Churn Analytics

* Churn by Contract Type
* Churn by Payment Method
* Churn by Customer Tenure
* Churn by Service Adoption
* Geographic Churn Distribution

### Predictive Analytics

* High-Risk Customer Identification
* Churn Probability Assessment
* Retention Opportunity Analysis

---

## 🔍 Key Business Insights

### 📌 Contract Type Matters

Customers on month-to-month contracts exhibit significantly higher churn rates compared to customers on long-term contracts.

### 📌 Customer Tenure Impacts Retention

New and short-tenure customers are substantially more likely to churn, highlighting the importance of onboarding and engagement strategies.

### 📌 Payment Behavior Influences Churn

Specific payment methods demonstrate stronger associations with customer attrition.

### 📌 Service Adoption Drives Loyalty

Customers utilizing multiple services show higher retention rates and lower churn probabilities.

---

## 🤖 Business Impact

* Identified critical churn-driving factors.
* Enabled early detection of at-risk customers.
* Supported targeted retention initiatives.
* Improved decision-making through predictive analytics.
* Demonstrated how Business Intelligence and Machine Learning can work together to solve real-world business challenges.

---

## 🚀 Skills Demonstrated

**SQL • Data Cleaning • ETL • Data Modeling • Power BI • DAX • Data Visualization • Python • Machine Learning • Random Forest • Predictive Analytics • Business Intelligence**

---

