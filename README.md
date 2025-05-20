# Predicting Bad Loans

How do banks distinguish “good” from “risky” borrowers? This is a project to predict which loan is likely to default.

## Background

Since 2007, the LendingClub has loaned at least US$10 billion thru its peer-to-peer lending platform. Approximately 12.51% of these loans are loans that were either charged off or likely to default (i.e. entered 2nd delinquency period of being late for 31 - 120 days). Link to the dataset on Kaggle: https://www.kaggle.com/datasets/ethon0426/lending-club-20072020q1/data

Given that a loan charge off results in direct financial loss to a bank, it is pertinent to identify what are the key factors that will indicate if a loan is likely to default.

## Extract, Transform, Load (ETL) Workflow

I extracted the datset with SQLite, transformed the data (i.e. data cleaning, exploratory data analysis, and building machine learning model), before loading it on Power BI to communicate the insights to business stakeholders. As part of the ETL workflow, comparisons against the borrower's annual income was made against their State's median household income. Data from United States Census Bureau was used: https://data.census.gov/table/ACSST1Y2019.S1901?q=S1901&t=Income+and+Poverty&g=010XX00US$0400000&moe=false

You may refer to the Jupyter notebook for the codes, the presentation deck for the summary of key insights and business actionables for non-technical stakeholders, and sample of the dashboard in pdf for deeper appreciation of the dataset for business stakeholders.
