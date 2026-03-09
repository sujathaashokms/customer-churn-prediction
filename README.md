# customer-churn-prediction
Machine learning project to predict customer churn in an e-commerce company using multiple classification models.
# Customer Churn Prediction for an E-Commerce Company

## Project Overview
Customer churn is a major challenge for e-commerce companies. Losing customers directly impacts revenue and growth.

This project develops machine learning models to predict which customers are likely to churn so that businesses can take proactive retention actions.

## Objectives
- Identify customers at risk of churning
- Understand factors driving churn
- Build predictive models for churn classification
- Provide business recommendations to improve customer retention

## Dataset
- 11,260 records
- 19 variables
- Data includes:
  - Customer demographics
  - Transaction behavior
  - Service interaction metrics
  - Revenue metrics

## Data Processing
Steps performed:

- Data cleaning
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Train-test split (70/30)

## Machine Learning Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Linear Discriminant Analysis
- Naïve Bayes
- Decision Tree
- Random Forest
- Bagging Classifier
- AdaBoost
- Gradient Boosting
- XGBoost

## Best Model

**Tuned KNN Model**

Performance:
- Recall (Churn): **96%**
- AUC Score: **99.4%**

This model performed best at identifying potential churners.

## Key Insights

Important churn factors:

- Customer tenure
- Complaints in previous year
- Marital status
- Cashback usage
- Customer service interactions

## Business Recommendations

- Introduce loyalty programs to increase tenure
- Improve customer service quality
- Target marketing for high-risk customer segments
- Increase cashback incentives
- Special retention offers for high-risk clusters

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Author

**Sujatha Mohan**
