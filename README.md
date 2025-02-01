# Loan Data Exploration
## by Robert Neubauer


## Dataset

I used Option 3: Loan Data on the communicate data findings page.


## Summary of Findings

During the exploration, BorrowerAPR, BorrowerRate, and CurrentDelinquencies were good indicators for what makes a loan risky or safe. As the credit grades got worse, the average APR and rate increased. In the final visualization, the amount of loans with more current delinquencies and higher APR increased.

Another variable I investigated was Loan status. I transformed the loan status variable from 12 to 4 kinds of statuses because outside of Current, Completed, Chargedoff, and Default, there was not a lot of data for the other statuses. Note that chargedoff means the bank took the loan as a loss. Looking into the relationship between Loan Status and current delinquencies, defaulted and chargedoff loans had more current delinquencies on average than completed and current loans.


## Key Insights for Presentation

For the presentation, I focused on visualizations that show credit grades compared to other variables. I first talk about credit grade and borrower rate with a violin plot for each credit grade. Second, I used a multivariable scatter plot with BorrowerAPR on the x-axis, CurrentDelinquencies on the y-axis, and each scatter plot as each credit grade. Lastly, I show a bar plot of Credit Score Range Upper and Credit Grade.