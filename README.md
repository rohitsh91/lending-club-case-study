# lending-club-case-study

## Table of Contents

## Introduction

Lending Club is a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
-	If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
-	If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

## Objective
Lending Club wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. This information can then be leveraged for its portfolio and risk assessment. We will use Exploratory Data Analysis technique to identify and analysis the loan.csv dataset.

## Technologies Used
Python, Pandas, Jupyter Notebook

## Analysis
### Data Understanding
- Understanding of the dataset and creation of dataframe from csv
### Data Cleaning
We performed bunch of data cleaning techniques to clean our data, we used the following methods:
- Column Treatment
- Removing data with 'Current' loan status
- Cleanup of emp_length column
- Formatting changes
- Datatype Changes
- Date Format Changes
- Value Substitution
- Adding missing values
- Outlier Treatment using Quartile method
- Deduplicate rows removal
- NaN value rows removal
- Derived Metrics

### Data Analysis
We performed operation of multiple columns and their combination using the following methodology:
- Univariate Analysis
- Segmented Univariate Analysis
- Derived Metrics
- Bivariate Analysis

### Recommendations
- Identified driver variables which could contribute for loan default based on the above analysis

##### Contributor
- Rohit Sharma
