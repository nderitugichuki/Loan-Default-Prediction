# Loan Default Prediction

## Dataset Description
The Loan Default Prediction dataset contains detailed information about loans issued by a financial institution. It can be utilized for predictive modelling to understand the factors contributing to loan defaults. The dataset comprises 255,347 entries and 18 columns covering various borrower demographics, financial details, and loan-specific attributes.

### File Overview
- **Filename**: `Loan_default.csv`
- **Size**: 35.1 MB
- **Number of Entries**: 255,347
- **Number of Columns**: 18

### Columns
1. **LoanID**: Unique identifier for each loan (object)
2. **Age**: Age of the borrower (int)
3. **Income**: Annual income of the borrower (int)
4. **LoanAmount**: Amount of loan issued (int)
5. **CreditScore**: Credit score of the borrower (int)
6. **MonthsEmployed**: Number of months the borrower has been employed (int)
7. **NumCreditLines**: Number of open credit lines the borrower has (int)
8. **InterestRate**: Interest rate of the loan (float)
9. **LoanTerm**: Term of the loan in months (int)
10. **DTIRatio**: Debt-to-income ratio of the borrower (float)
11. **Education**: Education level of the borrower (object)
12. **EmploymentType**: Employment status of the borrower (object)
13. **MaritalStatus**: Marital status of the borrower (object)
14. **HasMortgage**: Indicates if the borrower has an existing mortgage (object)
15. **HasDependents**: Indicates if the borrower has dependents (object)
16. **LoanPurpose**: Purpose of the loan (object)
17. **HasCoSigner**: Indicates if the loan has a cosigner (object)
18. **Default**: Target variable indicating if the borrower defaulted (1) or not (0) (int)

## Usage
This dataset can be used for various analyses, including:
- Predictive modeling to identify the likelihood of loan defaults.
- Exploratory data analysis to understand borrower and loan characteristics.
- Feature engineering and selection for machine learning models.
- Statistical analysis to determine significant factors affecting loan defaults.

## Getting Started
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/loan-default-prediction.git
   cd loan-default-prediction
   ```

2. **Install Required Packages**:
   Ensure you have the necessary Python packages installed. You can use the following command to install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. **Load the Dataset**:
   Use the following Python code to load and inspect the dataset:
   ```python
   import pandas as pd

   # Load the dataset
   file_path = 'Loan_default.csv'
   loan_data = pd.read_csv(file_path)

   # Display the first few rows
   print(loan_data.head())
   ```

## Repository Structure
- **Loan_default.csv**: The dataset file.
- **ipynb**: Contains the code documentation.
- **README.md**: This README file.
- **requirements.txt**: List of Python packages required for analysis (to be added based on your project needs).

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
We would like to acknowledge the financial institution that provided this dataset for educational and predictive modeling purposes.
