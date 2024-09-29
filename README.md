Loan Eligibility Prediction for Dream Housing Finance

Overview

Dream Housing Finance Company offers home loans across urban, semi-urban, and rural regions. 
Customers apply for loans, and the company validates their eligibility based on various personal and financial details. 
The goal of this project is to automate the loan eligibility process using customer data, enabling real-time predictions of loan approval.

Problem Statement

Dream Housing Finance aims to automate their loan eligibility process based on customer data such as Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others.
This automation will help the company target eligible customers more efficiently.

Data Dictionary

Train Data (train.csv)
The training dataset includes customers for whom the loan eligibility (Loan_Status) is already known.

Variable	Description
Loan_ID:	Unique Loan ID
Gender:Male/Female
Married	:Applicant married (Y/N)
Dependents	:Number of dependents
Education:	Applicant Education (Graduate/Under Graduate)
Self_Employed:	Self-employed (Y/N)
ApplicantIncome:	Applicant income
CoapplicantIncome:	Coapplicant income
LoanAmount:	Loan amount in thousands
Loan_Amount_Term:	Term of loan in months
Credit_History:	Credit history meets guidelines (1/0)
Property_Area:	Urban/Semi-Urban/Rural
Loan_Status:	Loan approved (Y/N) (Target variable)


Test Data (test.csv)
The test dataset contains customer information for which loan eligibility is to be predicted.
Variable	Description
Loan_ID:	Unique Loan ID
Gender:Male/Female
Married	:Applicant married (Y/N)
Dependents	:Number of dependents
Education:	Applicant Education (Graduate/Under Graduate)
Self_Employed:	Self-employed (Y/N)
ApplicantIncome:	Applicant income
CoapplicantIncome:	Coapplicant income
LoanAmount:	Loan amount in thousands
Loan_Amount_Term:	Term of loan in months
Credit_History:	Credit history meets guidelines (1/0)
Property_Area:	Urban/Semi-Urban/Rural

Evaluation Metric:
The performance of your model will be evaluated using Accuracy.Your predictions for loan status in the test dataset (test.csv) will be compared against the actual loan status values.
The submission file should contain the predicted loan status (Loan_Status) for each Loan_ID.

Approach

1)Data Cleaning & Preprocessing: Handle missing values, encode categorical variables, and scale numeric features.
2)Exploratory Data Analysis (EDA): Perform univariate and bivariate analysis to identify patterns and relationships between features.
3)Model Development: Train machine learning models (e.g., Logistic Regression, Decision Tree, Random Forest) to predict loan eligibility.
4)Model Evaluation: Evaluate the model’s performance using accuracy on the test dataset.
5)Prediction: Generate predictions for the test dataset and submit them for evaluation.
