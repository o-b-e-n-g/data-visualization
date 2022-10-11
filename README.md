# Influences of Loan features on Estimated Returns and Borrower APRs
## by Emmanuel Obeng


## Dataset

>This data set contains 113,937 loans from Prosper Funding LLC with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

> The data is one of Udacity's curated databases and was obtained from this [link](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.)


## Summary of Findings

> We identified a strong positive correlation of 0.8, between the Borrower APR and the Estimated Returns. The higher the Borrower APR, the more likely Prosper Loans LLC was expected to make returns on Loans given to Borrowers.

> We noted that the worse the credit rating, the greater the median Borrower APR. Additionally, the lower the income range of the borrower, the greater the median Borrower APR. This trend was similar with Estimated Returns too. We asserted that this could imply that the lower the income range of the borrower, and the worse the credit rating, the higher the risk of the loan and therefore, the higher interest rate which may lead to an increase in Borrower APR or Estimated Returns.

> This possibly explains why more loans were given out to borrowers with worse credit ratings when we explored the univariate distribution of our combined credit ratings. It is likely Prosper Loans gave out more high risk loans with the view of making more Returns from them.

> Finally, we noted a very weak correlation between Debt to Income ratio against both Borrower APR and Estimated Returns


## Key Insights for Presentation


> For the presentation, I just focus on features that mainly affect the Estimated Returns and Borrower APR. The key features would be incomes range and prosper rating. I would show both distributions of Estimated Returns and Borrower APR and the relationship between these two key variables. I would further explore the income range and combined credit rating variables and their relationships between Estimated Returns mainly. Since we indentified that Estimated Returns has a high correlation to Borrower APR, I would focus mainly on the Estimated Returns for my presentation. I would conclude by indentifying the effect loan term has on the features explored so far.