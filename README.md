## Blog:

https://medium.com/@hthdonghuy207/prosper-loan-data-analysis-59cd400f8aa9

## Installations

- Numpy
- Pandas
- matplotlib
- seaborn
- warnings

## File Descriptions

HuyTDD.ipynb: contain the analysis and code.

prosperLoanData.csv is the datasets.

## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. In order to make the visualization more simple, I have only looked at a few variables as the project says to focus on.

## Summary of Findings

> Information from Numerical variables analysis
- **StatedMonthlyIncome**: The monthly income the borrower stated at the time the listing was created. Most of the borrowers are having a salary less than 10000USD and the peak at nearly 5000USD
- **BorrowRate**: The Borrower's interest rate for this loan. The borrowers rate follow an approximately distribution with the peak nearly 0.16
- **LoanOriginalAmount**: The origination amount of the loan. It has multiple peaks at 4000USD, 10000USD and 15000USD
- **Investors**: The number of investors that funded the loan. Many investors between 0 and 100

> Information from Categorical variables analysis
- The loan with "C" category are highest the count
- Top IncomeRange of all Borrowers are within 50,000-74,999
- Top 2 states of all Borrowers are from CA and NY
- Majority of the borrowers are with an occupation of Professional and Executive
- The top 2 loan consideration reasons are 1 - Debt Consolidation, 2- Home Improvement

> Insights about the entire Bivariate analysis
- Loan original amount and monthly loan payment has strong correlated (with 0.92).Otherwise, borrowers rate and proper score are highly negative correlated
- The income range of employed is the highest
- LoanOriginalAmount is highest for A and B Prosper ratings, when compared with income range
- The most prosper rating is C with the range salary from 25k to 50k
- Employed are using the prosper rating C is the highest

> Insights from the multivate exploration data
- The average salaries of employed and full-time workers are higher
- With prosper ratings of AA,A and B, the monthly income of borrowers is higher for those who are employed, have other types of employment and work full-time
- Homeowners typically have lower interest rates as we can see. We can also plainly see that applications with higher HR prosper ratings have a higher interest rate


## Key Insights for Presentation

> The presentation, I focused on mainly the features that are impactful for approval of loanstatus.
The major insights obtained are:
- EmploymentStatus of all Borrowers are with Employed State
- Top IncomeRange of all Borrowers are within 50,000-74,999
- Majority of the borrowers are with an occupation of Professional and Executive
- Loan original amount and monthly loan payment has strong correlated (with 0.92).Otherwise, borrowers rate and proper score are highly negative correlated. Borrower interest rate and loanamount are -vely correlated.

Based on the applicants information, the loan approval status is heavily dependent on their income, homeownership status and employment status.