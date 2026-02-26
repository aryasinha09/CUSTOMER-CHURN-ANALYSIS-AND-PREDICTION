Customer Churn Analysis & Prediction

An end-to-end data analytics project focused on analyzing historical customer churn and predicting future churners using SQL, Power BI, and Machine Learning.

1) Business Objective

Customer churn directly impacts revenue and growth.
This project aims to:

* Identify key drivers behind customer churn

* Analyze churn patterns across demographic, geographic, and service dimensions

* Predict high-risk customers using Machine Learning

* Enable data-driven retention strategies

2) Tech Stack

* Microsoft SQL Server – ETL process, data cleaning, view creation

* SQL Server Management Studio – Database management

* Microsoft Power BI – Data modeling & interactive dashboards

* Python – Machine Learning implementation

* scikit-learn – Random Forest classifier

3) Project Workflow

 ETL in SQL Server

- Imported raw CSV data into staging table

- Cleaned null values & standardized categorical fields

- Created production table and analytical views

- Data Modeling in Power BI

- Built calculated columns (Churn Flag, Age Group, Tenure Group)

- Created DAX measures (Total Customers, Churn Rate, New Joiners)

- Designed interactive Executive Dashboard

Machine Learning Prediction

- Preprocessed categorical variables using label encoding

- Trained Random Forest model (80/20 split)

- Evaluated using confusion matrix & classification report

- Predicted churn risk for new customers

Dashboard Highlights

- KPI Cards: Total Customers, Total Churn, Churn Rate %, New Joiners

- Churn Analysis by Contract, Payment Method & Tenure

- Geographic churn distribution (Top States)

- Service-level churn analysis

- Dedicated Churn Prediction page for high-risk customers

 Machine Learning Impact

- Identified key churn-driving features

- Predicted high-risk customers before churn occurs

- Enabled proactive retention targeting

4 Key Insights

- Month-to-month contracts show the highest churn rate

- Short-tenure customers are more likely to churn

- Certain payment methods correlate with higher churn

- Service adoption significantly influences churn probability
