# Lending Club Case Study

A python based Exploratory data analysis of Lending Club loan dataset.

## Table of Contents
* [General Info](#general-information)
* [Libraries Used](#libraries-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A consumer finance company specializing in various types of loans to urban customers has provided a dataset of the past loans that were disbursed by the company. The dataset includes various consumer attributes and loan attributes. Consumer attributes include customer ID, location, annual income, credit inquiries, etc., Loan attributes include the loan amount, interest on the loan, installment to be paid, date of disbursal, etc., The loan attributes also includes the "loan status" which tells whether the loan is "Fully Paid" or "Charged off". Here, charged off means the loan is defaulted by the borrower.

Based on the past data, the company wants to identify the driving factors that impact the loan status (i.e. whether a loan would be fully paid or defaulted).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
From the data analysis on the Lending Club's loan data, we could figure out some of the driving factors that affect whether the loan will be fully repaid or defaulted. These factors include:
- Purpose of the loan taken
- Loan interest percentage
- Ratio of loan amount and annual income
- Revolving credit utilization percentage
- Number of credit inquiries made in the last 6 months
- Grade of the loan

The lender should be wary of these factors to avoid credit loss. For high default risk cases, the lender could ask the borrower to pledge collaterals. This could in turn help avoid financial loss for the lending company.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Libraries Used
- pandas - version 1.1.5
- seaborn - version 0.11.0
- matplotlib - version 3.5.3
- numpy - version 1.17.5
- scipy - version 1.7.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
