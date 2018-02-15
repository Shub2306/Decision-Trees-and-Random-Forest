# Decision-Trees-and-Random-Forest

Exploring publicly available data from LendingClub.com. Lending Club connects people who need money (borrowers) with people who have money (investors).I am trying to create a model that will help predict people who have a profile of having a high probability of paying back.

Lending club had a very interesting year in 2016. This data is from before they even went public.

I'm using lending data from 2007-2010 and trying to classify and predict whether or not the borrower paid back their loan in full. The data is downloaded from here

Here are what the columns represent:

credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
installment: The monthly installments owed by the borrower if the loan is funded.
log.annual.inc: The natural log of the self-reported annual income of the borrower.
dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
fico: The FICO credit score of the borrower.
days.with.cr.line: The number of days the borrower has had a credit line.
revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).


# Tree Methods using PySpark
  
A dog food company is trying to predict why some batches of their dog food are spoiling much quicker than intended! Unfortunately this Dog Food company hasn't upgraded to the latest machinery, meaning that the amounts of the five preservative chemicals they are using can vary a lot, but which is the chemical that has the strongest effect? The dog food company first mixes up a batch of preservative that contains 4 different preservative chemicals (A,B,C,D) and then is completed with a "filler" chemical. The food scientists beelive one of the A,B,C, or D preservatives is causing the problem,
  
Using Machine Learning with RF to find out which parameter had the most predicitive power, thus finding out which chemical causes the early spoiling! So creating a model and then find out how to can decide which chemical is the problem!
  
Pres_A : Percentage of preservative A in the mix  
Pres_B : Percentage of preservative B in the mix  
Pres_C : Percentage of preservative C in the mix  
Pres_D : Percentage of preservative D in the mix  
Spoiled: Label indicating whether or not the dog food batch was spoiled.
