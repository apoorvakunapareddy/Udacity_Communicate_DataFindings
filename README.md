# Udacity_Communicate_DataFindings


Introduction
I have selected the dataset prosper loan data analysis. The dataset contains peer-to-peer loan information for 113,937 loans with 81 variables on each loan from Prosper Funding LLC. I am going to explore the relationships among multiple variables using summary statistics and data visualizations.

Variable Selection for Analysis
After reviewing the data, I feel the below are most important variables.

BorrowerAPR: The Borrower's Annual Percentage Rate (APR) for the loan.
LoanAmount : The origination amount of the loan.
IncomeRange : The income range of the borrower at the time the listing was created. 
ProsperRating (Alpha):The Prosper Rating assigned at the time the listing was created between AA - HR.  Applicable for loans originated after July 2009.
DebtToIncomeRatio : The debt to income ratio of the borrower at the time the credit profile was pulled. 
Term: The length of the loan expressed in months.
MonthlyLoanPayment:The scheduled monthly loan payment.

In this project, I have tried to identify the correlation between these metrics using univariate, bivariate and multivariate analysis. Also, I have tried to understand how the relationship between the main variables gets impacted when a supporting variable included in the analysis. I have used “Term “ and  “Prosper rating” as my secondary variables. These variables helped me understand the pattern of my key variables better. Please refer the python file to get in-depth details of my analysis.
