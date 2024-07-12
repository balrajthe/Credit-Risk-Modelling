# Credit-Risk-Modelling

<p align="center">
<img src="https://dm0qx8t0i9gc9.cloudfront.net/thumbnails/video/UD7CEz6/bank-building-clouds-time-lapse-office_qjos54lu_thumbnail-1080_01.png" height="200px">
</p>


## Problem Definition
This project tackles a multiclass classification issue by analyzing customer banking performance based on their repayment history and bank track records. The objective is to classify each customer into one of the four categories: High Potential, Moderate Potential, Low Potential, or Zero Potential.

## Data Collection
Data was sourced from two primary origins: bank records and customer CIBIL history. This dataset includes customer details, transaction history, credit scores, and repayment records. More specifics are provided in the "Features_Target_Description.xlsx" file.

## Data Exploration and Analysis
Extensive Exploratory Data Analysis (EDA) was conducted to understand the dataset. This process involved identifying patterns, trends, and anomalies, as well as visualizing relationships between different features.

## Data Preprocessing
Data cleaning was performed to address missing values, outliers, and duplicates. Categorical variables were encoded, and the dataset was divided into training, validation, and test sets to ensure robust model evaluation.

## Feature Engineering
Feature engineering, including scaling and encoding, was performed as required to enhance the dataset.

## Model Selection
Various machine learning algorithms, such as Decision Trees, Random Forest, and XGBoost, were considered. The choice of algorithms was informed by the multiclass nature of the problem.

## Model Training
The selected models were trained on the training dataset. Hyperparameters were fine-tuned using cross-validation to optimize performance and prevent overfitting.

## Model Evaluation
Models were assessed using the validation and test datasets. Metrics such as accuracy, precision, recall, and F1-score were used to measure performance. The ROC-AUC score was also evaluated for comprehensive assessment.

## Model Interpretation
Model predictions were analyzed to understand their reasoning. Techniques such as feature importance and SHAP values were employed to explain the impact of different features on the model’s decisions.

## Model Deployment
The best-performing model was prepared for local deployment. An executable (.exe) file was created for local installation. Users can provide unseen data in .csv format to a specified folder, and the executable will process and generate predictions for the entire file.

## Model Monitoring and Maintenance
The model’s performance is continuously monitored to ensure ongoing accuracy. Regular updates and retraining are planned to incorporate new data and enhance the model.

## Documentation and Presentation
All project steps were thoroughly documented in the Readme.md and Feature Explanation sheet. These files have been uploaded to the GitHub repository, providing users with the necessary information to replicate the project.

## Project Review and Reflection
Ongoing feedback from bank employees and stakeholders is essential to validate the accuracy of customer classifications. Incorrect classifications will be corrected, and the model retrained to improve accuracy. Credit Risk Modelling is an iterative process requiring continuous refinement.

## Future Improvements
Continuous efforts are made to enhance the project. Potential improvements include incorporating more data from other banks and credit agencies, considering additional factors beyond credit agency reports such as current customer performance and mortgage offerings. Another improvement could be reducing dataset dimensionality for easier integration into a web-based interface where users can input specific information to receive customer potential classifications.

## Basics of Banking Terminology to Understand the Dataset

### Asset Products
Asset products in banking refer to financial products that are assets for the bank, typically because they generate income through interest or fees. These include:
- **Loans:** Money lent to individuals or businesses with the expectation of repayment with interest.
- **Mortgages:** Long-term loans secured by real estate.
- **Credit Cards:** Lines of credit extended to customers, allowing them to borrow funds up to a pre-approved limit.
- **Overdrafts:** Extensions of credit granted when account balances are insufficient to cover transactions.
- **Investments:** Financial products such as bonds, equities, and other investment vehicles that banks use to earn returns.

### Liability Products
Liability products are financial products that are liabilities for the bank, as they involve the bank owing money to customers. These include:
- **Savings Accounts:** Deposit accounts that pay interest on the balance held.
- **Current Accounts:** Deposit accounts that allow for frequent transactions, such as withdrawals and deposits.
- **Fixed Deposits (FDs):** Term deposits where money is deposited for a fixed period at a fixed interest rate.
- **Recurring Deposits (RDs):** Deposit accounts where customers make regular deposits and earn interest.
- **Certificates of Deposit (CDs):** Time deposits with a fixed term and interest rate.

### Trade Line
A trade line is a record of activity for any type of credit extended to a borrower and reported to a credit reporting agency. It includes information such as the type of credit, the date it was opened, the credit limit or loan amount, the account balance, and the payment history.

### Types of Loans
There are various types of loans available, including:
- **Personal Loans:** Unsecured loans for personal use, such as home renovations or medical expenses.
- **Home Loans:** Loans specifically for purchasing or renovating a home.
- **Auto Loans:** Loans for purchasing vehicles.
- **Student Loans:** Loans for financing education.
- **Business Loans:** Loans to support business activities.
- **Payday Loans:** Short-term, high-interest loans typically due on the borrower’s next payday.

### Secured Loans
Secured loans are loans that are backed by collateral, which the lender can seize if the borrower defaults. Examples include:
- **Home Loans (Mortgages):** Secured by the property being purchased.
- **Auto Loans:** Secured by the vehicle being purchased.
- **Secured Personal Loans:** Secured by assets such as savings accounts or certificates of deposit.

### Unsecured Loans
Unsecured loans are loans that are not backed by collateral. The lender relies on the borrower’s creditworthiness and ability to repay. Examples include:
- **Personal Loans:** Not backed by any specific asset.
- **Credit Cards:** Lines of credit not secured by any asset.
- **Student Loans:** Typically not secured by any asset.

### Non-Performing Asset (NPA)
A Non-Performing Asset (NPA) is a loan or advance for which the principal or interest payment remained overdue for a period of 90 days or more. NPAs are an indication of the financial health of the bank and affect its profitability.

### Delinquency in a Bank Account
Delinquency refers to a situation where a borrower is late or overdue on a payment. Delinquencies can affect a borrower’s credit score and may lead to penalties, higher interest rates, or other consequences.

### Days Past Due (DPD)
Days Past Due (DPD) is a measure of the number of days a payment is overdue. It is used to assess the timeliness of payments and the likelihood of default. For example, a DPD of 30 means the payment is 30 days late.

By understanding these terms, one can better understand the datasets at hand and ascertain the financial health of borrowers and institutions to take better decisions for the bank or financial institutions.

