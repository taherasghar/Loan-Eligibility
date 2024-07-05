# Loan Eligibility Prediction
## Problem Statement
Dream Housing Finance company deals in all home loans. Customers first apply for a home loan, and the company then validates their eligibility. The goal is to automate this loan eligibility process (in real-time) based on customer details provided in the online application form. We aim to create a model that identifies customers eligible for a loan.

## Dataset Description
The loan_eligibility dataset includes customer details such as Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and more. The Loan_Status column represents the loan status, where 'Y' indicates approval and 'N' indicates rejection.

## Libraries Used
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy

## Exploratory Data Analysis
Drop Irrelevant Columns: Removed columns that do not have predictive power, such as Loan_ID.
Summary of Dataset: Reviewed dataset information to understand data types and non-null counts.
Frequency Distribution: Examined the distribution of values in the Loan_Status column.
Missing Values: Identified and handled missing values in the dataset.
Duplicates: Checked for and removed any duplicate rows.
Outliers: Removed outliers to improve model performance.
Data Preparation
Handling Missing Values: Imputed missing values using appropriate methods (mode, mean).
Removing Outliers: Used z-score to identify and remove outliers.
Transforming Data: Encoded categorical variables using LabelEncoder.
Data Visualization
Bar Charts: Visualized the distribution of various features.
Heatmap/Correlation Matrix: Examined the correlation between features and Loan_Status.

## Model Training and Testing

### Methodology
Our AI model automates the prediction of loan eligibility using a supervised machine learning model, specifically a decision tree classifier. Decision trees provide clear, interpretable results based on customer attributes, making it easier to understand the factors influencing loan decisions.

### Model Selection
We chose the decision tree model for its ability to handle categorical features naturally and provide clear rules for classification.

### Training and Testing
Feature Vector and Target Variable: Defined X (features) and Y (target variable).
Data Splitting: Split the data into training and testing sets.
Model Fitting: Trained the decision tree classifier on the training set.
## Results
The model achieved an accuracy ranging from 68% to 75%, indicating reasonable success in predicting loan eligibility. The decision tree model provides clear outcomes based on real-life factors affecting loan approval, which is convincing for customers.
