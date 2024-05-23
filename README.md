# Risk Weighted Assets and Capital Requirement for bank's mortgage portfolio under IRB and Standardized approach

# Project overview
## 1. Defining business problem
Calculate Risk Weighted Assets and capital requirement for the bank's residential mortgage portfolio, under both: standardized and IRB approach and compare the results.

## 2. Data set description
Mortgage_default dataset, which contains loans with a status indicator: defaulted(bad) or non-defaulted.

Description of data columns:

•	BAD: 1 = applicant defaulted on loan or seriously delinquent; 0 = applicant paid loan

•	MORTDUE: Amount due on existing mortgage

•	VALUE: Value of current property

•	JOB: Occupational categories

•	YOJ: Years at present job

•	DEROG: Number of major derogatory reports

•	DELINQ: Number of delinquent credit lines

•	CLAGE: Age of oldest credit line in months

•	NINQ: Number of recent credit inquiries

•	CLNO: Number of credit lines

•	DEBTINC: Debt-to-income ratio

All given loans in the dataset are mortgage loans

For the lines with missing collateral values, use default LTV = 0.45

Dataset shape: 11 columns; 5960 rows

The raw data set is in the project’s Excel file. 

## 3. Analysis steps
The project is presented in an uploaded Excel file. The file contains an overview of the project in the first tab.

The project overview includes information about: steps taken, description of each step, details and insights, link to the tab or file with details for that step.

Suggested approach to review the project: go to the Project Overview tab, review each step, if necessary go to the tab/file with details for that step (you can use provided links).

Logistic regression, as part of this project, has been prepared in Python and is provided in the uploaded Jupyter Notebook.

Additionally, separate presentation has been prepared and uploaded in the PDF file, to present the results of the analysis to the business.

Analysis steps overview:

1.	Data evaluation
2.	Recognizing columns for RWA and capital requirement calculation under Standardized approach
3.	Data preparation for calculating RWA and capital requirement under standardized approach
4.	Calculating LTV and applying risk-weights under standardized approach
5.	Calculating RWA and Capital requirement under Standardized approach
6.	Recognizing columns for capital requirement calculation under F-IRB approach
7.	Data preparation for logistic regression for PD prediction
8.	Determining PD (logistic regression)
9.	Calculating RWA under IRB approach for Unexpected Loses: not-defaulted exposures
10.	RWA under IRB approach for Unexpected Loses: defaulted exposures
11.	Calculation of Expected Losses
12.	Internal definition of exposures in default
13.	Summary and insights
14.	Preparing presentation of analysis results

