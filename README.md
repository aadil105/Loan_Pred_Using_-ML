# Loan Prediction using Machine Learning
This project demonstrates a loan prediction model using various machine learning algorithms such as Random Forest, Decision Tree, Naive Bayes, and K-Nearest Neighbors. The dataset used contains information on loan applicants, and the goal is to predict whether a loan will be approved or not based on the applicant’s details.

 
Project Overview
The objective of this project is to build a machine learning model that can predict loan approval based on the financial history and characteristics of loan applicants. The project uses a variety of classification algorithms and compares their performance.

Dataset
The dataset used is loan.csv, which contains the following columns:

Loan_ID: Unique loan identifier
Gender, Married, Dependents, Education, Self_Employed: Personal information
ApplicantIncome, CoapplicantIncome: Financial details
LoanAmount, Loan_Amount_Term: Loan details
Credit_History: Credit score history
Property_Area: Type of property
Loan_Status: Target variable indicating loan approval status


Features
New features were engineered, such as:

TotalIncome: Combined income of the applicant and coapplicant
Logarithmic Transformations: Applied to some variables to normalize their distribution
Preprocessing
Handled missing values using mode and mean imputation
Applied label encoding for categorical features
Standardized numerical features using StandardScaler
Models Used



The following models were trained and evaluated:

Random Forest Classifier: Accuracy = 71.54%
Decision Tree Classifier: Accuracy = 71.54%
K-Nearest Neighbors (KNN): Accuracy = 55.28%
Gaussian Naive Bayes: Accuracy = 27.64%


Results
The Random Forest and Decision Tree classifiers provided the highest accuracy at 71.54%, while K-Nearest Neighbors and Naive Bayes showed lower performance.

