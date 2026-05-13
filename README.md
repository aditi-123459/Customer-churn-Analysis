# Customer Churn Analysis 📊

## Overview
This project focuses on analyzing customer churn behavior using Python, Machine Learning, and Power BI. The objective is to identify patterns behind customer churn, build predictive models, and visualize business insights through an interactive dashboard.

Customer churn refers to customers who stop using a company’s services or products. Predicting churn helps businesses improve customer retention and reduce revenue loss.

 

# Dataset
Dataset Source:  
https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset

 
# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Power BI

 

# Project Workflow

## 1. Data Collection
- Imported customer churn dataset from Kaggle

## 2. Data Cleaning
- Removed missing values
- Removed duplicate records
- Converted categorical variables into numerical format

## 3. Exploratory Data Analysis (EDA)
Performed detailed analysis using:
- Churn distribution analysis
- Tenure analysis
- Usage frequency analysis
- Support calls analysis
- Payment delay analysis
- Correlation heatmaps

## 4. Machine Learning Models
Built and compared multiple machine learning models:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

## 5. Model Evaluation
Evaluated model performance using:
- Accuracy Score
- Confusion Matrix
- Classification Report

## 6. Feature Importance
Identified important factors affecting customer churn:
- Tenure
- Usage Frequency
- Support Calls
- Payment Delay

## 7. Dashboard Creation
Created an interactive Power BI dashboard including:
- KPI Cards
- Churn Analysis
- Customer Segmentation
- Subscription Analysis
- Interactive Filters

 

# Key Insights

- Customers with low tenure are more likely to churn
- Low usage frequency strongly contributes to churn
- Customers with high support calls have higher churn probability
- Premium subscribers show better retention rates
- Payment delays are associated with increased churn risk

 

# Machine Learning Models Used

| Model | Purpose |
|-------|---------|
| Logistic Regression | Baseline classification |
| Decision Tree | Rule-based prediction |
| Random Forest | Improved accuracy and stability |
| XGBoost | Advanced predictive performance |

 

# Power BI Dashboard Features

- Total Customers KPI
- Churn Rate KPI
- Churn Distribution
- Churn by Gender
- Churn by Subscription Type
- Tenure Analysis
- Interactive Slicers and Filters

 

# Project Structure

```bash
Customer-Churn-Analysis/
│
├── dataset/
│   └── customer_churn_dataset.csv
│
├── notebook/
│   └── churn_analysis.ipynb
│
├── dashboard/
│   └── Customer_Churn_Dashboard.pbix
│
├── images/
│   └── dashboard_screenshots/
│
└── README.md
 

 

# Installation

Install required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
```

 

# Running the Project

1. Download the dataset
2. Open Jupyter Notebook
3. Run all cells in the notebook
4. Open Power BI dashboard file for visualization

 
# Business Impact

This project helps businesses:
- Identify customers likely to churn
- Improve customer retention strategies
- Reduce revenue loss
- Enhance customer satisfaction
- Make data-driven decisions

 

# Future Improvements

- Hyperparameter tuning
- Deep learning implementation
- Streamlit or Flask deployment
- Real-time churn prediction
- Cloud deployment

 

# Conclusion

This project demonstrates a complete end-to-end data analytics and machine learning workflow, including:
- Data preprocessing
- Exploratory data analysis
- Predictive modeling
- Dashboard visualization
- Business insight generation

It showcases practical skills in:
- Data Analysis
- Machine Learning
- Business Intelligence
- Data Visualization
- Problem Solving

---
