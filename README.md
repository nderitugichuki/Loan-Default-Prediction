# Loan-Default-Prediction
Loan Default Prediction Dataset
Dataset Description
This dataset contains detailed information about loans issued by a financial institution. The dataset can be used for predictive modeling to understand the factors that contribute to loan defaults. It consists of 255,347 entries with 18 columns, covering various borrower demographics, financial details, and loan-specific attributes.

File Overview
Filename: Loan_default.csv
Size: 35.1 MB
Number of entries: 255,347
Number of columns: 18
Columns
LoanID: Unique identifier for each loan (object)
Age: Age of the borrower (int)
Income: Annual income of the borrower (int)
LoanAmount: Amount of loan issued (int)
CreditScore: Credit score of the borrower (int)
MonthsEmployed: Number of months the borrower has been employed (int)
NumCreditLines: Number of open credit lines the borrower has (int)
InterestRate: Interest rate of the loan (float)
LoanTerm: Term of the loan in months (int)
DTIRatio: Debt-to-income ratio of the borrower (float)
Education: Education level of the borrower (object)
EmploymentType: Employment status of the borrower (object)
MaritalStatus: Marital status of the borrower (object)
HasMortgage: Indicates if the borrower has an existing mortgage (object)
HasDependents: Indicates if the borrower has dependents (object)
LoanPurpose: Purpose of the loan (object)
HasCoSigner: Indicates if the loan has a cosigner (object)
Default: Target variable indicating if the borrower defaulted (1) or not (0) (int)
Usage
This dataset can be used for various analyses, including but not limited to:

Predictive modeling to identify the likelihood of loan defaults
Exploratory data analysis to understand the characteristics of borrowers and loans
Feature engineering and selection for machine learning models
Statistical analysis to determine significant factors affecting loan defaults
Getting Started
Clone the repository:

sh
Copy code
git clone https://github.com/yourusername/loan-default-prediction.git
cd loan-default-prediction
Install required packages: Ensure you have the necessary Python packages installed. You can use the following command to install the dependencies:

sh
Copy code
pip install -r requirements.txt
Load the dataset: Use the following Python code to load and inspect the dataset:

python
Copy code
import pandas as pd

# Load the dataset
file_path = 'Loan_default.csv'
loan_data = pd.read_csv(file_path)

# Display the first few rows
print(loan_data.head())
Repository Structure
Loan_default.csv: The dataset file
README.md: This readme file
requirements.txt: List of Python packages required for analysis (to be added based on your project needs)
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
We would like to acknowledge the financial institution that provided this dataset for educational and predictive modeling purposes.

