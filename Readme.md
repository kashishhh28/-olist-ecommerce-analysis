# Olist E-Commerce Analysis

## Overview
End-to-end analysis of Brazilian e-commerce data from 
Olist platform covering sales, delivery, customer behavior 
and machine learning predictions.

## Dataset
Olist Brazilian E-Commerce Dataset from Kaggle
- 5 CSV files merged into one master dataset
- 100,000+ orders from 2016 to 2018

## Tools Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, XGBoost
- Power BI

## Project Structure
1. Data Cleaning & Feature Engineering
2. Exploratory Data Analysis (EDA)
3. Revenue at Risk Analysis
4. RFM Analysis & Customer Segmentation
5. Machine Learning Models
6. Power BI Dashboard

## Key Findings
- São Paulo generates 38% of total revenue
- R$ 1.2M revenue at risk due to late deliveries
- 97% customers purchase only once
- Credit card preferred by 77% customers
- Remote states pay 2x more freight costs

## RFM Customer Segments
| Segment | Description |
|---|---|
| Champions | Buy recently, often and spend most |
| Loyal Customers | Buy regularly with good spending |
| Big Spenders | High spending but less frequent |
| At Risk | Haven't bought in a long time |

## ML Models
| Model | Task | Result |
|---|---|---|
| Linear Regression | Predict delivery days | R2 = 0.05 |
| Logistic Regression | Predict late delivery | Accuracy = 95% |
| XGBoost | Predict late delivery | Accuracy = 96% |

## Business Recommendations
- Focus marketing in top 5 cities
- Partner with local couriers in remote states
- Offer EMI options for higher value purchases
- Re-engage At Risk customers with discount emails
- Reward Champions with loyalty programs
