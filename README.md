# Lending Club Case Study
> In this case study, I have analyzed a loan dataset to find out the attributes determining the risk of default. I have used exploratory data analysis in Python to find out critical consumer and loan attributes which are driver variables behind loan default. Therefore, a bank must assess these variables before lending to identify risky applicants.

## Table of Contents
* [General Info](#general-information)
* [Work Undertaken](#work-undertaken)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The project intends to inform banks decision on lending to a loan applicant regarding the various attributes that need to be considered before lending decision.
- When a consumer finance company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision: If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
- The loan data set contains the complete loan data for all loans issued through the time period 2007 t0 2011. It contains the information about past loan applicants and whether they ‘defaulted’ or not. The data contains information about 110 variables apart from loan status which includes identifiers, consumer attributes, loan attributes, and post charge-off information. I have used consumer attributes and loan attributes to find out the drivers using EDA.

## Work Undertaken
- Data cleaning and preparation
- Univariate and segmented univariate analysis
- Bivariate analysis
- Derived metrices
- Multivariable analysis

All analysis are exploratory and relies on visual assessment and does not contain hypothesis testing and model building.

## Conclusions
- Risky drivers to be considered for hypothesis formulation and testing and modelling thereafter include:
    1. 60 month tenure
    2. Loan grade E and F
    3. Rent more than mortgage
    4. Source verified income
    5. 1 derogatory public record
    6. More recent ECRs
    7. Higher interest rates
    8. More enquiries in last 6 months
    9. Lesser description sentiment score
    10. More revolving utilization
    11. More DTI
- Charge off is more with higher number of total accounts when open accounts are more.
- Lower annual income irrespective of loan amount, but with higher interest rates have greater frequency of charge off.
- The extreme positive of sentiment score of description along with large description may result in more likely charge off.
- More inquiries in last 6 months with less revolving balance is more likely to get into charge off.
- Income less than 80K along with higher employment length and loan tenure of 60 months are more likely to charge off.

## Technologies Used
Python - version 3.7.12
Libraries used:
- numpy 
- pandas 
- matplotlib 
- seaborn 
- plotly 
- plotly express
- re 
- nltk
- wordcloud
Notebook: Google Colab Pro+

## Acknowledgements
I gratefully acknowledge the contribution of the following for completing this project.
- This project was inspired by the upGrad and IIITB under the Executive PG Programme in Machine Learning and AI.
- References: Credit risk modelling in Python by Paul Bananzi (2020) [available at : https://medium.com/analytics-vidhya/credit-risk-modelling-in-python-3ab4b00f6505], Credit risk analysis with Machine Learning by Rafael Bastos (2020), [available at: https://towardsdatascience.com/credit-risk-analysis-with-machine-learning-736e87e95996], Data mining with R- Capstone assignment 7 [https://rstudio-pubs-static.s3.amazonaws.com/303215_bb3e159757314931ac706574b96162b7.html], A complete guide to plotting categorical variables with Seaborn by Will Norris (2021) [https://towardsdatascience.com/a-complete-guide-to-plotting-categorical-variables-with-seaborn-bfe54db66bec], Processing and visualizing multiple categorical variabl;es with Python - NBA's schedule challenges by JP Hwang (2020) [https://towardsdatascience.com/processing-and-visualizing-multiple-categorical-variables-with-python-nbas-schedule-challenges-b48453bff813]
- This project was based on datasets provided by upGrad.

## Contact
Created by [@drkaushiksarkar] - feel free to contact me!
