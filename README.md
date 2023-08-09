## Customer-Churn-Prediction
## by Oluseye Oyeniran
---
![](Customer_churn_image.jpg)

***

## Introduction
_ _ _

In this comprehensive project, we adopt an all-inclusive approach to predict customer churn by identifying specific criteria that indicate the likelihood of customers discontinuing their services.

---

Customer churn, also referred to as customer attrition or customer defection, is a term used to describe the situation when customers terminate their association with a business or cease utilizing its products or services. It reflects the rate at which customers disengage or end their involvement with a company within a specific timeframe. The primary objective of this project was to predict potential churn customers using historical data provided by our client. It involved a classification problem that utilized a supervised machine learning approach. To begin the analysis, I formulated queries to join tables and extract the necessary data from the database. Through data exploration and transformation, and employing statistical techniques such as Variance Inflation Factor, Recursive Feature Elimination, and assessment of multicollinearity, I reduced the initial set of 158 derived features to the most crucial eight features. These selected features were utilized as the final set for prediction. The predictive model successfully identified over 4,000 potential churners, which has the potential to generate an additional annual revenue of over $2,000,000 for the business.

## Problem Statement

The main challenge addressed in this Python-based project is to accurately forecast potential customer churn utilizing historical data, as supplied by our client.

## Data Sourcing and Integration

The project's data is sourced from the Client Database, encompassing transactional, behavioral(acquired through RFM analysis), attitudinal, and demographic data. To extract the necessary information for analysis, tailored SQL queries were formulated. These queries efficiently gathered the diverse data components from the database.
Integration of the data was achieved by seamlessly linking the database with a Python Jupyter Notebook. This integration was enabled through the utilization of the Pandas library for data manipulation and the pyodbc library for connecting to the database. This streamlined process facilitated efficient data access and transformation, laying the foundation for subsequent analysis and insights.

Attiudinal Data       |  Demographic Data
:---------------:     |:----------------:
 ![](attitudinal.png) | ![](demographic_query.png)  


Transactional Data       |  Behavioral Data
:---------------:     |:----------------:
 ![](Transactional.png) | ![](behavioral.png) 
