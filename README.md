#  Prosper Loan Analysis
## by Greatness Okeremeta


## Dataset

> The Prosper loan data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.


## Summary of Findings

> In exploring the data, I found a strong negative correlation between the loan amount and the borrower’s interest rate. The largest number of loans fell between the 0.1 and 0.3 interest rates with a few loans with interest rates less than 0.1. The interest rate is rightly-skewed with a sharp peak around 0.32 for ~4,000 loans. Unemployed individuals saw their interest rates increase every year, with a marked increase in 2013. All income groups saw a slight decrease in their interest rates in 2012.  Only borrowers in the $50,000 - $74,999 income range saw an increase in interest rates in 2014. For Individuals in the $1 - $24,999 income range, the sharp drop in their interest rates in 2014 was noteworthy, it became the lowest interest rate for all income groups in the year.

> Most of the loans in the data set are current loans with the majority of them rated - C, followed by completed and charged-off loans, most of which are rated - D. The defaulted loans are quite few compared to the completed loans. The loans that were past their due date were split based on the length of delay in repayment. An overwhelming amount of active loans are past their due date by 1 - 15 days. It was observed that most of the defaulted loans come from individuals with high Prosper ratings. The 36 month tenor was the most preferred of the 3 available loan terms.

> Most of the borrowers are employed with a significant number of them in full-time employment. The population of people that are self-employed is slightly higher than those in other forms of employment. The lower Prosper ratings have more borrowers with the employment status - Self-employed and Other. When analysed with the Prosper ratings, the employment status - Employed, has a normal distribution.

> People that earn between $50,000 and $75,000 take the most loans, they're closely followed by those in the $25,000 - $49,999 income range. There is a positive correlation between the loan amount and the monthly payment. The loan original amount steadily increased from 2009 to 2012 for all income groups. The unemployed individuals had a sharp drop in their loan original amounts in 2013. These 3 income groups - ($100,000+, $25,000 - $49,999 and $50,000 - $74,999) - had an increase in their original loan amounts every year under review. As loan amount increased, so did the Prosper rating. This isn’t surprising as the borrowers who take on heavier loans, tend to earn more. They would get lower interest rates, it is assumed that they can afford to pay higher monthly payments, the negative correlation between the interest rate and the loan original amount supports this. It was also noticed that the borrowed amounts increased in the last few years, while the average interest rate decreased. It was interesting to see that the defaulted loans for individuals with high Prosper ratings tend to be larger than completed loans. One would expect that these individuals would have a higher number of completed loans since the data suggests that they earn more than the others. Generally, most of the defaulted loans were obtained for home improvement purposes. These loans were the only loan category that saw more defaults than completions. 

> California is the state with the highest value of loans taken. This isn't surprising as most of the borrowers live in the state. Wyoming had the fewest number of borrowers. Most of the individuals were first-time borrowers with Prosper, they had no prior loans at the time of listing. A significant number of borrowers had only 1 prior loan while a few individuals had 2+ prior loans. Most of the loans were taken to consolidate debt while students took the least number of loans. The Loans for students use had the least amount of defaults.


## Key Insights for Presentation

> I start the presentation by introducing the distribution of the loan status categories, active loans and the loan interest rates/borrow rates. This provides insight into the structure of the loans being analysed. 

> I subsequently explore the relationship between these variables and other features of interest in the data like the prosper rating, loan amount, loan origination date and income range. To achieve this I use: the count plot for (Loan Status and Prosper Rating) and (Prosper Rating and Employment Status),  regression plot for the Borrower Rate and Loan Original Amount, the point plot to explore the relationship between Loan Origination Year, Borrower Rate & Income Range, boxplot for Loan Status, Loan Original Amount and Prosper Rating and the violin plot for Listing Category, Loan Original Amount and Loan Status.