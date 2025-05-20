
# **Customer Churn Prediction – Subscription Service**

This end-to-end data analysis and machine learning project focuses on predicting customer churn for a fictional subscription-based service. It showcases the full data science lifecycle from data generation, exploration, feature engineering, modeling, and business insight extraction — providing a strong demonstration of applied analytical thinking.

---

## Problem Statement

Churn represents a loss of revenue and potential growth for subscription-based businesses. Without a clear understanding of what drives customers to leave, companies risk higher marketing costs and missed revenue.  

This project aims to:
- Predict churn using key behavioral and subscription features
- Identify the most influential drivers of churn
- Provide actionable recommendations to reduce churn

---

## Project Goals

- Simulate realistic subscription customer data
- Perform statistical and visual exploratory data analysis
- Build predictive models to classify churn
- Interpret results to inform business decisions
- Package insights into a format suitable for stakeholders and recruiters

---

## Dataset Overview

A synthetic dataset of 2,200 customers was generated with the following fields:

| Feature | Description |
|---------|-------------|
| CustomerID | Unique ID |
| Gender | Male/Female |
| Age | Age in years |
| Subscription_Type | Basic, Premium, Enterprise |
| Tenure_Months | Duration of subscription |
| Monthly_Spend | Monthly payment |
| Total_Spend | Total lifetime spend |
| Support_Tickets | Number of support interactions |
| Payment_Method | Wallet, Card, Bank Transfer |
| Auto_Renew | Yes or No |
| Churn | Target variable (1 = Churned, 0 = Active) |

---

## Tools Used

| Tool | Use Case |
|------|----------|
| Python (Pandas, NumPy) | Data simulation, transformation |
| Seaborn & Matplotlib | Visualizations |
| scikit-learn | Encoding, model building, evaluation |
| Jupyter Notebook | Exploratory and iterative analysis |

---

## Project Workflow

1. **Data Simulation**: Created realistic customer data with built-in churn logic  
2. **Exploratory Data Analysis**: Analyzed distributions, relationships, and target behavior using:
   - Count plots
   - Box plots
   - Heatmaps
3. **Data Preprocessing**:
   - Encoded categorical variables
   - Removed unnecessary identifiers
   - Split data into train/test
4. **Modeling**:
   - Logistic Regression as baseline
   - Random Forest for feature importance & higher performance
5. **Evaluation**:
   - Accuracy, precision, recall, F1-score
   - Confusion matrix and feature importance visualizations

---

## Key Insights

- **Auto-renew** was the strongest predictor of retention  
- Churn rates were higher among customers with fewer months of tenure  
- Customers with **higher support ticket activity** churned more often  
- Premium and Enterprise users churned less than Basic subscribers  
- Actionable Insight: Improve onboarding and customer support for new users on the Basic plan

---

## Visuals

- Churn Distribution by Segment  
- Feature Importance via Random Forest  
- Confusion Matrix for classification performance

---

## What This Project Demonstrates

- Business-first framing of a machine learning problem  
- Clear understanding of the modeling lifecycle  
- Proficiency with data visualization and feature interpretation  
- Skill in using tools like Python, scikit-learn, and Jupyter notebooks  
- Effective storytelling and communication for stakeholders

---

## Deliverables

| File | Description |
|------|-------------|
| `customer_churn_data.csv` | dataset |
| `churn_model_notebook.ipynb` | All code and analysis in one place |
| `churn_visuals.png` | Plots of model insights |
| `README.md` | This summary document |

