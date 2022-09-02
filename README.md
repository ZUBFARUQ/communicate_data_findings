# Loan Data from Prosper Exploration
## by Umar Faruq Zubairu


## Dataset

> This data set contains information on peer to peer loans facilitated by credit company **Prosper**. There are 113,937 loans with 81 variables. For the purpose of this investigation, I've taken the following variables: MemberKey, Term, LoanStatus, BorrowerRate, ListingCategory (numeric), EmploymentStatus, StatedMonthlyIncome, TotalProsperLoans, LoanOriginalAmount, Recommendations and Investors.


## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.
- The majority of borrowers are **Employed** and the second most frequent category is **Full-time.** Furthermore, the least frequent categories are **Not Employed** and **Retired**. This finding will be good to be presented.

- Most of the loans in the dataset are current loans. Past due loans are splitted into several groups based on the length of payment delay.

- With a boundary of mean and 3 times standard deviations distribution of monthly stated income still has noticeable right skew but now we can see that mode is about 5000. 428 outliers are noticed as well.

- Majority of the loans' term has the length of 3 years (36 months). The least frequent term is 1 year-lenght (12 months).

- Borrowers that have least amount of prior loans are the one that completed their loans the most.

- Borrowers with **Full-time** employment status are the one that completed their loans the most. Moreso, The defaulted loans are also having a higher frequency of **Full-time** employers.

- **Defaulted** credits tend to be `smaller` than **completed credits** onces.

- Other than the Other Listing category which comprises of different Listings the borrower selected, Debt Consolidation Listing has the highest frequency of employment status.

- The plot shows that in almost all the listings of `Listing Category (numeric)`, borrowers with highest `Loan Original Amount` have a status of Completed loan.

- The plot shows that, Borrowers with *Employed* status tends Complete their loan despite the Loan Original Amount being the highest.


## Key Insights for Presentation

I've chosen key plots with high data-to-ink ratio for the presentation. The plots I've chosen shows distribution of main variables, Loan status, stated monthly income, Listings category and I've tried to tell a story that are major predictors for loan status and Listings category variables.