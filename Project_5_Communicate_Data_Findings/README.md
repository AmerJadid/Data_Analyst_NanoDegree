# Loan Data from Prosper

## by Amer Jadid


## [Dataset](https://docs.google.com/spreadsheets/u/0/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing)

>This data set contains 113,937 loans with 81 variables on each loan, including loan amount,
borrower rate (or interest rate), current loan status, borrower income, and many others.
The data can be found in Udacity's amazon S3 Bucket under this link: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv
This data dictionary that explains the variables is under this link: https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1588750841252000


## [Summary of Findings](https://github.com/AmerJadid/Data_Analyst_NanoDegree/blob/master/Project_5_Communicate_Data_Findings/exploration_loan_data_from_prosper.ipynb)

> In the exploration, I found that there was a significant relationship between
the Loan Status and the Borrower Rate (interest rate), also a high association
between Loan Status and whether the borrower is a homeowner, borrower
has a verifiable income and the credit/prosper score, with some modifying effects
from the Listing Category, Stated Monthly Income. The relationship is clearly
visible on the median or mean interest rate for each of our Loan Status categories,
where borrowers with lower median/mean interest rate have a lower risk of defaulting,
also, I found that a risk of being default or charged-off on a loan is higher for borrowers
that does not own a home, their income is not verifiable, and they tend to have a low credit/prosper score.

> Outside of the main features, I found that as Loan Original Amount have a high association
with the Borrower Rate where borrowers tend to borrow more money at low interest rates,
and not surprisingly the same is True for Monthly Loan Payment and Stated Monthly Income
with Borrower Rate, as there is a very high association between the Loan Original Amount
and the Monthly Loan Payment, where technically, they represent same variable.

> To see a pattern inside the loan count itself, loans are being plotted with time to see if
there is a trend in the borrowing behavior, where we can clearly see that the count of
loans decreased significantly, reaching almost Zero in the middle of the recession period, from
2007-12-01 to 2009-06-01 and then recovered gradually till 2013, then exponentially after 2013.



## [Key Insights for Presentation](https://github.com/AmerJadid/Data_Analyst_NanoDegree/blob/master/Project_5_Communicate_Data_Findings/slide_deck_loan_data_from_prosper.ipynb)

> In this presentation, I focused on the effect of income verifiable,
if the borrower is a homeowner, credit score, and prosper score on the
loan status outcome. I started by plotting and explaining the
distribution or the count of the loan status.

> Afterwards, I plotted the count of Loan Status by date to explain the count
of defaulted and completed loan trend overtime. Then I have plotted different
variables such as the stated monthly income, loan monthly payments and the loan original
amount against the interest rate to explain how these variables interact with
each other and with the interest rate.

> For the main feature of interest, I have explained how the income verifiable and
if the borrower is a homeowner effect the loan status outcome in addition to this
I had explained the effect of credit grade and prosper score on the loan status.
All of these variables is explained in conjunction with interest rate.

> Finally, a Choropleth Map for High Risk Loans in United Status is plotted
where I explained how the geolocation of the borrower is affecting the loan outcome.</br>

Link to [data](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)
