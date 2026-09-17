# Customer Churn Prediction using Machine Learning

## Project Overview

This project predicts whether a telecom customer is likely to churn using machine learning.

The analysis uses customer demographic, service, contract, tenure, and billing information to identify patterns associated with customer churn.

## Dataset

- Total customers: 7,043
- Features used: 30 after preprocessing
- Target variable: Churn
- Churned customers: 1,869
- Customers who stayed: 5,174

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Encoding
5. Train-Test Split
6. Feature Scaling
7. Logistic Regression
8. Random Forest
9. Model Evaluation
10. Feature Analysis

## Business Insights

- Month-to-month contract customers had a substantially higher churn rate than customers on one-year and two-year contracts.
- Customers who churned had a lower average tenure than customers who stayed.
- Customers who churned had higher average monthly charges.
- The model identified contract type, tenure, monthly charges, and internet service as important factors in churn prediction.

## Model Results

| Model | Accuracy | Churn Recall | Churn F1-Score |
|---|---:|---:|---:|
| Logistic Regression | 80.48% | 57% | 61% |
| Random Forest | 79.28% | 51% | 57% |

The results are based on the project's train-test split.

## Feature Analysis

The Logistic Regression coefficients were analyzed to understand which features were most strongly associated with the model's churn predictions.

Key features included:

- Internet service type
- Total charges
- Streaming services
- Contract type
- Monthly charges
- Customer tenure

Positive coefficients indicate greater association with the model predicting churn, while negative coefficients indicate greater association with predicting non-churn.

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Categorical Encoding
- Feature Scaling
- Machine Learning
- Model Evaluation
- Data Visualization
- Business Insight Generation

## Project Files

- `Customer_Churn_Prediction.ipynb` — Complete analysis and machine learning workflow

## Author

Srujana
