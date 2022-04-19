# Loan Data Exploration

## Dataset

There are 113937 loan records in the dataset with 80 features out of which 30 important features and 84853 records will be considered for this our analysis due to their relevance in determining the amount of loan to be collected and prosper rating. 
Majority of the variables are numeric (float and imteger) in nature, but the variable LoanOriginationDate is in datetime after careful convertion while the remaining features are categorical in nature.
The dataset can be found in  [here](https://github.com/OLAMIDE100/Udacity-Data-Visualisation-Project-/blob/main/cleaned_loada_data.csv),
with feature documentation available [here](https://github.com/OLAMIDE100/Udacity-Data-Visualisation-Project-/blob/main/Prosper%20Loan%20Data%20-%20Variable%20Definitions%20-%20Sheet1.pdf).


## Summary of Findings

In the exploration, I found that 
* LoanOriginalAmount has a right skewed distribution, 
with a lot of loan listing on the low LoanOriginalAmount end, and few on the high LoanOriginalAmount end.

* Highest percentage of the loan listing was carried out in the 4th quarter, followed by the 1st quarter and lastly by the 2nd quarter of the year, 
with the 1st quarter recording the highest average loan amount for the years the survey was carried out

* Based on yearly analysis from the chart we can see that 2013 recorded the highest loan listing with 2014 topping the chart for average loan amount requested for

* Members with prosperating C had the highest record of loan listing with relatively low number of members with prosperating AA from the survey, 
though AA topped the chart for average loan original amount this should be attached to thier high prosper rating

* Majority of the listing are coming from Carlifonia,New York,Texas, Florida with Washington, D.C topping the average loan amount recorded as expected

* borrower rate and borrower APR shows strong positive correlation

* borrower rate and Prosper rating shows strong negative correlation

* prosper rating and loan amount shows slighty strong positive correlation


## Key Insights for Presentation

For the presentation, I focus on just the influence the 30 selected features both categorical and numerical have on
the loan original amount and prosper rating. I start by selecting the important variable in this 
my analysis, followed by the univaraite chats against loan orignal amount and record count , then correlation plot.

