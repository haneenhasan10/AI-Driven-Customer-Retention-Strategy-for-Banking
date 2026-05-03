**Bank Customer Churn Prediction & Retention Dashboard**
**Project Overview**

This project aims to help banks proactively reduce customer turnover (churn) using Machine Learning. Most churn models only show who has already left; this solution focuses on Future Risk Analysis, identifying high-risk customers who are still active so the bank can intervene and retain them.

The Data Science Pipeline
The project was executed through a full data science lifecycle:

1. Exploratory Data Analysis (EDA)

Analyzed a dataset of 10,000 customers 


2. Machine Learning Modeling

Preprocessing: Categorical encoding (LabelEncoder), Feature Scaling (StandardScaler).

Model Choice: Employed LightGBM and Random Forest with a "Balanced" class weight approach to prioritize the minority churn class.

Output: The model generates a Churn Probability Score for every customer.


3. Business Intelligence Dashboard (Power BI)

I integrated the ML output with Power BI to create an actionable tool for the retention team.

Current Customer Status: Overview of active vs. churned totals.

Future Risk Analysis: A list of active customers with a probability score > 0.70.

Risk Segmentation: Customers categorized into High, Medium, and Low risk based on ML predictions.


Key Insights from Dashboard

 - High-Risk Segment: Identified 182 customers at critical risk (score > 80%).

 - Product Analysis: Customers with 3 or more products show an unusually high churn rate.


Tools Used
Python: Pandas, Scikit-learn, LightGBM, Seaborn.

Power BI: Data visualization and Risk categorization.

GitHub: Project documentation.
