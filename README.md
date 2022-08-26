# Prosper Loan Data Exploration
## by Kenneth Odoh


## Dataset

The data consists of information regarding 113,937 loan entries from a peer-to-peer lending marketplace, including loan status, total principal borrowed, income range, and other debtor and loan information. The dataset can be found [here](https://www.google.com/url?q=https://www.google.com/url?q%3Dhttps://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv%26amp;sa%3DD%26amp;ust%3D1581581520570000&sa=D&source=editors&ust=1661465763533082&usg=AOvVaw18IT4SYLXwYGKDViP9OkMv), with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

## Summary of Findings

In the exploration, I found that Employment status of borrowers have a strong influence on their loan status. The employed ones displayed higher likeliness to pay their debts, while the retired and unemployed were more likely to default their loans or incure chargeoffs. It was further confirmed that across most employment statuses, those with verifiable incomes are more likely to pay their debt. 
Majority of the debtors borrowed to spend, rather than invest. Also, there were more debtors with verifiable income status than those without.
There were also more debtors borrowing lower principals (below \\$10k) than those borrowing higher principals. A two-sided effect was found of principal borowed on loan status. Debtors who borrowed lower principals displayed higher loan completment rate, but at the same time, had higher tendencies to incure bad debts.

## Key Insights for Presentation

For this presentation, I will focus on the influence of income status of borrowers on loan repayment. First, I will introduce the primary variable, followed by the distributions of other variables of interest. Afterwards, I will introduce the plots showing the influence of each of the secondary variables on the primary variable. Finally, I will introduce the chart showing a combined effect of employment status and income verifiability on loan status.