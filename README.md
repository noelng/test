# Loan-Risk-Assessment

Loan risk assessment is a critical task in the lending industry. It involves evaluating the likelihood of a borrower defaulting on a loan, and assigning a risk score based on their creditworthiness, financial history, and other relevant factors. The risk score helps lenders determine whether to approve the loan, and at what interest rate. However, accurately assessing loan risk is a complex and challenging task, requiring the analysis of large amounts of data, including credit reports, financial statements, and loan repayment histories. In this problem, we aim to use machine learning to build a loan risk model that can accurately predict the risk of default for new loan applications. By doing so, we can help lenders make more informed decisions about which loans to approve, and at what terms, ultimately reducing their overall risk exposure and improving their bottom line.

In this problem, we will be using 'loanStatus' from loan.csv as the target variable: <br>

The target variable is categorized into 2 classes:<br>
Class 'High' - meaning loans that are in high risk of defaulting<br>
Class 'Low' - meaning loans that are in low risk of defaulting<br>

Values in 'High': <br>

Internal Collection, External Collection, Returned Item, Charged Off Paid Off, Settled Bankruptcy, Settlement Paid Off, Charged Off and Settlement Pending Paid Off<br>

Values in 'Low': <br>

Paid Off Loan, New Loan and Pending Paid Off<br>

The advantage of binary class classification compared to multi-class classification in this case is predict_proba() can be used to visualized the probability of an application loan risk status to be either 'High' or 'Low', giving us the flexibility to manipulate and filter the applicants according the desired threshold<br>
