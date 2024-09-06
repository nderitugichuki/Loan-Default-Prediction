# Loan-Default-Prediction
Loan Default Prediction Dataset
Overview
This dataset contains records related to loans issued by financial institutions, with the goal of predicting whether a loan will default or not. The dataset includes demographic information about the borrowers, loan details, and other features that could impact the likelihood of default.

Dataset Summary
Total Records: 255,347
Total Features: 18 (17 input features and 1 target variable)
Features:
LoanID - Unique identifier for each loan.
Age - Age of the borrower (in years).
Income - Annual income of the borrower (in currency units).
LoanAmount - The total loan amount issued.
CreditScore - The credit score of the borrower.
MonthsEmployed - Number of months the borrower has been employed.
NumCreditLines - Number of active credit lines.
InterestRate - The interest rate of the loan (percentage).
LoanTerm - Duration of the loan (in months).
DTIRatio - Debt-to-income ratio.
Education - The highest educational level attained by the borrower (e.g., Bachelor's, Master's, High School).
EmploymentType - The type of employment (e.g., Full-time, Part-time, Unemployed).
MaritalStatus - Marital status of the borrower (e.g., Married, Divorced).
HasMortgage - Whether the borrower has a mortgage (Yes/No).
HasDependents - Whether the borrower has dependents (Yes/No).
LoanPurpose - Purpose of the loan (e.g., Business, Auto, Other).
HasCoSigner - Whether the borrower has a co-signer (Yes/No).
Default - Target variable (1 = defaulted on the loan, 0 = did not default).
Usage
This dataset is ideal for building classification models aimed at predicting whether a borrower will default on a loan. It can be used for:

Logistic Regression
Decision Trees
Random Forests
Gradient Boosting Machines
Neural Networks
The dataset allows for experimentation with feature engineering and model tuning to improve the accuracy of predictions.

File Information
Filename: Loan_default.csv
Size: ~35 MB
Format: CSV
License
This dataset is provided for educational purposes. Please ensure that you comply with relevant regulations when using financial data.
