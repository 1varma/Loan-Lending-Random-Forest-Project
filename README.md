# Lending Club Random Forest Project

Welcome to the Lending Club Random Forest Project! In this project, we delve into publicly available data from LendingClub.com, a platform that connects borrowers with investors. Our goal is to develop a model that predicts the likelihood of borrowers paying back their loans in full. This prediction is crucial for investors seeking to make informed decisions about where to invest their money.

## Project Overview

Lending Club experienced a significant year in 2016, making it an interesting period to analyze. The data we'll be using predates their public offering and spans from 2007 to 2010. We'll focus on classifying borrowers based on whether they paid back their loans in full. The dataset has already been cleaned of any missing values, making it ready for analysis.

## Dataset Description

The dataset contains the following columns:

- **credit.policy**: Indicates whether the customer meets LendingClub.com's credit underwriting criteria (1 for yes, 0 for no).
- **purpose**: Describes the purpose of the loan, such as "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", or "all_other".
- **int.rate**: The interest rate of the loan, represented as a proportion.
- **installment**: The monthly installments owed by the borrower if the loan is funded.
- **log.annual.inc**: Natural logarithm of the self-reported annual income of the borrower.
- **dti**: Debt-to-income ratio of the borrower (debt divided by annual income).
- **fico**: FICO credit score of the borrower.
- **days.with.cr.line**: Number of days the borrower has had a credit line.
- **revol.bal**: The borrower's revolving balance (unpaid amount at the end of the credit card billing cycle).
- **revol.util**: The borrower's revolving line utilization rate (credit used relative to total available credit).
- **inq.last.6mths**: Number of inquiries by creditors in the last 6 months.
- **delinq.2yrs**: Number of times the borrower had been 30+ days past due on a payment in the past 2 years.
- **pub.rec**: Number of derogatory public records (bankruptcy filings, tax liens, or judgments) associated with the borrower.

## Getting Started

You can download the dataset from the provided link or use the provided CSV file, which is already cleaned of NA values. Feel free to explore the data and implement a random forest model to predict loan repayment behavior.

## Let's Begin!

Get ready to dive into the world of predictive modeling with the Lending Club Random Forest Project. Analyze the data, build your model, and uncover insights that can guide investment decisions. Happy exploring! 🌟
