# SaaS Customer Churn Prediction

## Overview

Customer churn is one of the most significant challenges faced by subscription-based businesses. Retaining existing customers is often more cost-effective than acquiring new ones. This project focuses on analyzing customer behavior and building machine learning models to predict which customers are likely to leave a SaaS (Software as a Service) platform.

The objective is to help businesses proactively identify at-risk customers and implement retention strategies before churn occurs.

---

## Business Problem

A SaaS company wants to reduce customer attrition by identifying customers who are likely to cancel their subscriptions.

By leveraging customer demographic information, service usage details, contract information, and billing data, machine learning models can be trained to predict customer churn and provide actionable business insights.

---

## Dataset

This project uses the IBM Telco Customer Churn Dataset.

The dataset contains customer-level information including:

- Demographic details
- Customer account information
- Subscription services
- Contract type
- Internet services
- Monthly charges
- Customer tenure
- Churn status

---

## Project Objectives

- Understand customer churn behavior
- Perform exploratory data analysis (EDA)
- Identify factors contributing to churn
- Build predictive machine learning models
- Evaluate model performance
- Generate business recommendations to improve customer retention

---

## Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

### Development Environment
- Google Colab

### Version Control
- GitHub

---

## Machine Learning Workflow

### 1. Data Understanding
- Dataset inspection
- Data type analysis
- Missing value assessment

### 2. Data Cleaning
- Handling missing values
- Removing unnecessary columns
- Preparing data for modeling

### 3. Exploratory Data Analysis (EDA)
- Churn distribution analysis
- Contract type analysis
- Monthly charges analysis
- Tenure analysis
- Correlation analysis

### 4. Feature Engineering
- Encoding categorical variables
- Preparing model-ready features

### 5. Model Building
The following machine learning models were implemented:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

### 6. Model Evaluation
Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve

### 7. Feature Importance Analysis
Important predictors of customer churn were identified to support business decision-making.

---

## Key Insights

The analysis revealed several important factors influencing customer churn:

- Customers with month-to-month contracts were more likely to churn.
- Customers with shorter tenure showed higher churn rates.
- Monthly charges had a significant impact on customer retention.
- Contract type was one of the strongest predictors of churn.
- Customer service and subscription characteristics played a major role in churn behavior.

---

## Results

The machine learning models were successfully trained and evaluated on customer churn data.

Performance metrics were analyzed to compare different algorithms and identify the most effective model for churn prediction.

The project demonstrates how machine learning can be used to support customer retention strategies and reduce revenue loss caused by customer attrition.

---

## Business Recommendations

Based on the analysis, the following recommendations can help reduce churn:

1. Encourage customers to move from month-to-month plans to long-term contracts.
2. Improve onboarding experiences for new customers.
3. Develop targeted retention campaigns for high-risk customers.
4. Monitor customer satisfaction and service usage patterns.
5. Provide personalized offers to customers likely to churn.

---

## Project Structure

```text
saas-churn-prediction/
│
├── Telco_customer_churn.xlsx
├── churn_analysis.ipynb
└── README.md
```

---

## Future Improvements

Potential enhancements for this project include:

- Hyperparameter tuning
- Cross-validation
- Streamlit deployment
- Interactive dashboard development
- Real-time churn prediction system
- Cloud deployment

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Feature Engineering
- Machine Learning
- Model Evaluation
- Business Analytics
- Predictive Modeling
- GitHub Project Management

---

## Author

**Akshaya Kommu**

Master of Science in Data Science  
Montclair State University

### Connect With Me

- GitHub: https://github.com/AkshayaK2001
- LinkedIn: *(Add your LinkedIn profile URL here)*

---

## License

This project is intended for educational and portfolio purposes.
