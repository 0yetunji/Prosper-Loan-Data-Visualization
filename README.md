# Prosper-Loan-Data-Visualization
# Prosper Loan Data Visualization
## by Tunji Abdulfatai


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The data can be found here https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv. and the  variable dictionary here https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0


## Summary of Findings

> The Prosper rating chart shows a similar distribution from the left to the right. The median rating 'C' also happens to be the modal rating. AA has the minimum number between 4500-5000 in the group. The distribution of the loan amount on standard scale has a long tailed distribution. Therefore,a log scale is applied to it. Using a log scale shows a major peak between 4000− 5000 and two minor peaks, one betwen 14000− 15000 and the other between 20000− 25000. The distribution appears to be two tailed.

>The loan original amount increases with an increase in the number of investors, Prosper score, and Income range.

The borrower APR decreases with an increase in prosper score,income range, and available bank credit.

The two main features of interest turns out to have a negative relationship between them.

> Number of Investors increases with the income range and also income range and prosper ratings increases with each other therefore showing a positive relationship between the pair.

> I further explored the relationship between the two variables of interest with a third variable of prospers rating. It indicated that low ratings attract high APR and low loan ammounts. While high ratings is associated with low APR and high loan amounts.

> A surprising interaction is the relationship between borrower APR and Loan amount moving from negative to positive as the prosper ratings changes from HR to AA.


## Key Insights for Presentation
> I focused my interest on the factors that are best in predicting the loan original amount and the Borrower APR.

> The features i expect to support my investigation includes prosper score, loan status, income range, available bank card credit,and employment status which I introduced using various plots

> A log transform was applied to the Investor's  and the Loan Original ammounr plot after the initial plot retrned a long tailed distribution. from the log-scaled distribution, it can be seen that majority of the investors per loan is one and the borrower rate distribution indicates a peakjust around 0.31 and 0.32. The histogram just cuts off to an end at 0.35 rather than running a tail.

> This prosper loan analysis started with some wrangling where a subset of variables were first extracted for exploration. Variables were first explored univariatly before moving to bivariate and multivariate exploration. The visualization revealed a couple of interesting insights and observations about the loan data.

The borrower APR is high for loans that are small and bigger loans attract small APR. This appears to be so just to encourage borrowers to go for bigger loans which brings back more money to the investors.

The prosper score and rating has a big influence on the amount given to borrowers. Borrowers with good ratings are given larger amount of loan compared to those with poor ratings.
