# Prosper-Load-Dataset-Exploratory-and-Explanatory-Analysis
The original dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. Most variables are numeric in nature, but the variables such as CreditGrade, LoanStatus, ProsperRating(Alpha), ListingCategory, Occupation, EmploymentStatus, IncomeRange, and IsBorrowerHomeowner are categorical variables.  

The dataset features can be split into three main categories:  Borrowers data Loan data Credit Risk metrics However, since we cannot explore the entire 81 variables, 16 variables of interest were pre-selected and explored. This variables include some of the borrower's information, loan data, and credit risk metric.


During my research, I discovered that the borrower APR is inversely connected with the original loan amount. The APR varies greatly depending on the loan amount, although the range of APR decreases as the loan amount increases. Borrower APR also reduces when the credit score improves. Borrowers who have received the highest Prosper ratings have the lowest APR. This suggests that the Prosper rating has a significant impact on borrower APR. Interestingly, when the Prosper grades are raised from HR to A or above, the link between borrower APR and loan amount shifts from negative to slightly positive.This might be due to the fact that persons with A or AA credit scores prefer to borrow more money, and increasing the APR could prohibit them from borrowing even more. People with poorer credit scores tend to borrow less money, therefore lowering the APR may encourage them to borrow more. I also discovered that for those with HR-C grades, the borrower APR decreases as the loan duration lengthens. However, for persons with B-AA credit scores, the APR rises as the loan duration lengthens.

Other insights about the borrowers that were reavealed are;

The state with the highest population of loan takers is California (CA) while North Dakota has the least population
Debt Consolidation appears to be the most popular reason for taking loans.
Majority of the borrowers have a job (either part time or full time) with income ranging between USD 25,000 and USD 74,999 and has a loan tenor of 36 months.
Borrowers who are employed take out a larger loan than those who are retired or unemployed. Borrowers who are jobless pay a higher interest rate than those who are working or retired.
Most borrowers Debt to Income (DTI) ratio falls betweet 20% and 35%. Lenders want a debt-to-income ratio of no more than 36% according to investopedia.



I looked at factors that predicts the borrower’s APR as well as the effect of the the borrowers' occupation and employment status on the loan amount. As suspected, the interest rate and lender yield has an effect on the APR of the borrower such that as the APR increases, the interest rate also increases.

Furthermore, the borrower APR and the original loan amount were negatively correlated, which means that the larger the loan, the lower the APR.

It also makes sense that the borrowerAPR, rate, and lenderyield are negatively correlated to prosper score because borrowers with lower score are more likely to pay higher APR and will definitely been given the loan at a higher rate
