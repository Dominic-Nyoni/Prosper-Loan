# (Prosper Loan Dataset)
## by (Dominic Nyoni)


## Dataset

The data consists of information regarding 113,937 loans from ProsperLoans, including
LoanStatus, BorrowerRate, and more information about loans.The dataset was sourced from https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv while the Data dictionary was collected from https://docs.google.com/spreadsheet/d/1gDyi_L4UvlrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtl/edit#gid=0  

## Summary of Findings

Exploration of the Prosper Loans dataset  indicates that Prosper Score and BorrowerRate/interest rate have the most effect on the loan outcome status.In particular,borrowers who have high prosper scores and interest rates below 20% tend to complete payment of their loans as opposed to borrowers with low to average prosper scores and interest rates over 20%.The distribution of prosper scores among borrowers who completed their loan payments show that high prosper scores(7-10) are a clear majority while the low scores(below 5) are the least frequent.

## Key Insights for Presentation

For the presentation,I only focus on the effect of interest rate and prosper score on the outcome status of loans.I start off with showing the distribution of loan statuses.I then present violin plots side by side plotting intrest rate vs prosper score and intrest rate vs loan status.Lastly, I present a bar highlighting the distribution of prospers scores among borrowers who completed their payments.One thing to note is that for presentation I melted categories in the prosper scores from the initial 1-10 to the following: lowscore(1-4); avgscore(5-6) and highscore(7-10).For loan status, i melted the categories to those who completed and those who totally failed to make their payments.