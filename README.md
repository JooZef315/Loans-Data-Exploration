# Loans Data Exploration

### udacity data analyst nanodegree project

## Dataset

> This data set contains 84853 loans originated after July 2009. 12 features [Term, LoanStatus, BorrowerAPR, BorrowerRate, LenderYield, EstimatedReturn, ProsperScore, EmploymentStatus,EmploymentStatusDuration, IsBorrowerHomeowner, LoanOriginalAmount, MonthlyLoanPayment]. Most variables are numeric, but the variables IsBorrowerHomeowner is bool and EmploymentStatus, IncomeRange are category.
link: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv
feature documentation: https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0


## Summary of Findings

> The multivariate exploration here showed that there indeed is a negative effect of increased MonthlyLoanPayment and LoanOriginalAmount on BorrowerAPR, 
we can see that larger values of APR (0.3:0.4) tend to come with smaller values of Monthly Loan Payment and also Loan Original Amount, 
it is interesting that with small values of APR (0:0.2) the MonthlyLoanPayment and LoanOriginalAmoun have no significant effect. 
and people who earn larger Income or own Houses tend to Borrow larger loans. 
we found that the correlation coefficient between LenderYield and BorrowerAPR is very high. 
we also see a negative correlation coefficient between BorrowerAPR and ProsperScore.

## Key Insights for Presentation

> For the presentation, I focus on just the correlation between BorrowerAPR with variables (MonthlyLoanPayment, IncomeRange). and the relation between LoanOriginalAmoun with with variables (IsBorrowerHomeowner, IncomeRange).
I start by introducing the BorrowerAPR variable, followed by the pattern in MonthlyLoanPayment distribution, then plot the scatterplot. 
Afterwards, I introduce each variable one by one using histograms and bar plots. then, I am using box plot, scatter plots, and heat maps to show the relations, afterwards, using FacetGrid.
