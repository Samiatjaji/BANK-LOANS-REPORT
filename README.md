# BANK-LOANS-REPORT

![form](https://github.com/user-attachments/assets/9996cfa9-abe0-42cf-86f3-180a29d460b4)

# Introduction 
This is an excel project on a bank loan data from the US in the year 2021. This project is to analyse and derive insights to answer critical questions and allow these Insights/answers provided to be used to make better decisions going forward as a bank.

# Dataset used
The dataset was downloaded from kaggle. Download [here](https://github.com/Samiatjaji/BANK-LOANS-REPORT/blob/main/financial_loan.csv)

# Data Analysis process
A series of steps must be carried out to interpret this information. The steps i used in this process are listed below:
- Excel concept applied
- Problem Statement 
- Data Cleaning Process
- Visualisation 
- Communication and insights

## Problem Statement 
To analyse this data I would like to highlight the main focus, reasons and questions I will be answering with the data analysis process, to gain a comprehensive overview of the bank's lending operations and monitor the performance of loans.  
This analysis will focus on:
### Primary KPIs,  Month over Month (MoM) and  Month to Date (MTD) changes 
- Total loan Applications
- Total funded amount 
- Total amount received 
- Average interest rate 
- Average Debt to income ratio (DTI)
- Good Loans vs Bad Loans
### Secondary KPIs
- Monthly Trends by Issue date
- Regional analysis by state
- Loan term analysis 
- Employee length
- Loan purpose 
- Home ownership analysis 

## Data Cleaning Process 
The dataset used was a clean one. I had to convert from a csv to xlx file and created a pivot table to start visualizing it. I also created a new column and used the IF( OR) statement to categorise the loan status into good or bad loans. 

![IF statement](https://github.com/user-attachments/assets/654fdc3f-16f8-4e31-ad17-381ccdafc294)


All further analysis are in the design sheets of the interactive [dashboard](https://github.com/Samiatjaji/BANK-LOANS-REPORT/blob/main/Dashboard%20Analysis.xlsx)


## Visualisation
The whole visualisation was done using pivot charts in excel

### Summary Dashboard 

![Summary Report](https://github.com/user-attachments/assets/c1d58ba5-8213-4a33-ae78-0ee9592a0018)

At the top, KPIs such as total applications, total funded amount, total amount received, average interest rate and average DTI are displayed alongside their month-over-month and month-to-date changes showing performance trends.

![KPIs](https://github.com/user-attachments/assets/cf916956-e5cc-4e6f-8400-1e447a614fd2)


- The total loan application is 38.6K with a month-over-month increase of 6.9% and month-to-date of 4.3K application. This indicates an positive trend in loan demand and that the bank is actively attracting new loan applicants.
- The total funded amount by the bank is $435.8M with MoM increase of 13% and MTD of $54.0M. This shows that the bank is succesffully approving and funding a significant portion of loan applications.
- The total amount received is $473.1M with MoM increase of 15.8% and MTD of $58.1M shows that repayments are coming in at a healthy pace
- The average Interest rate is 12.05% with MoM increase of 3.5% and MTD of 12.36%
- The Average Debt-to-income ratio is 13.33% with MoM increase of 2.7% and MTD of 13.67% further suggests that borrowers may have a relatively high level of existing debt. This could pose a risk to loan repayment.

- Good Loans Issued vs Bad Loans
![Good Bad loans](https://github.com/user-attachments/assets/3a58867b-3dbe-4e84-aa32-39b6c26b4d55)

Out of the Total Applications of loans approved, 86.18% of them were good loans (i.e a payment plan has been paid fully or still ongoing). This is 33.2K of total applications and funded amount is $370.2M while the amount received is $435.8M.  This shows that adequate requirements and practices are being followed to ensure repayment of loans.
Meanwhile, Bad Loans (5.3K applications) only amount to 13.82% of the total applications where $65.5M applications were funded and $37.3M was received back.This is low compared to good loans but its still a potential area for risk management improvement. 

- Secondary KPIs

![Fully paid etc](https://github.com/user-attachments/assets/8ceef71d-2843-4650-9cb5-486fd7d65290)

The dashboard provides a breakdown of loan performance based on the loan status using a grid view report in order to completely cover the data and hence enforce the right decisions on the bank's health Portfolio. 
Majority of loan applications (32.1K) have been fully paid off ($351.4M) indicating a positive trend while a smaller portion (5.3K) have been charged off and some loans are currently active and being repaid (1.1K). The fully paid category has the highest funded amount ($351.4M) reflecting a significant volume of repaid loans while the "charged off" category has a funded amount of $65.5M representing a loss for the bank. The Interest rates vary across loan statuses with "current" loans generally having a higher interest rate (15.10%). The DTI also varies across loan statuses including potential risk factors associated with "charged off" (14.72%) 

### Overview Dashboard 

![Overview Report](https://github.com/user-attachments/assets/ecdc9651-c026-419c-8f9b-33f233d7588a)

- Total Loan Application by Month

![Total loan by month](https://github.com/user-attachments/assets/fc4c0df5-f516-4e9d-a951-51dc8737eaac)

The chart clearly shows an upward trend in loan applications throughout the year. The number of applicants steadily increases from January to December with Decemeber having the highest loan applications (4.3K)

- Total Loan Application by State 

![Total Loan by state](https://github.com/user-attachments/assets/199aec4c-fe55-421d-9580-33a9236bf968)

The map visually represents the distribution of loan applications across different states in the United States. The color intensity indicates the number of loan applications with darker colors representing higher application volumes. States like ---- with higher costs of living might have a highr demand for loans for their expenses such as housing and education.

- Total Loan Application by Term

![Total Loan by term](https://github.com/user-attachments/assets/227e65b6-39e2-495e-bbd2-6c9b15c4660e)

When it comes to Loan Term, Borrowers generally prefer short term loans to long term loans. 28.2K applicants take loans within 36 months repayment plan while 10.3K take the 60 months plan.  

- Total Loan Application by Employee length 

![Total Loan by employee length](https://github.com/user-attachments/assets/e1700195-cd89-4091-b2cd-13ca7a6b280e)

The chart shows that employees with longer tenure (10+ years) has a significant higher loan application rates (8.9K). However this growth is not consistent, it is notice that employees with 1 year length (3.2K) have more application rates more than employees of 6,7,8 and 9 years. This maybe due to the fact that these shorter lenth employees (<1,1,2,3,4,5) have more needs that their income can't afford so they tend to reach out for bank loans more.

- Total Loan Application by Purpose

![Total Loan by employee purpose](https://github.com/user-attachments/assets/8bb9f0f1-c3f7-44ee-ba41-bf6b41774909)

This chart needs to be expanded more than this visualisation to show that Loans due to Debt Consolidation is the highest, This shows that a very high proportion of loan applications (18.2K) are driven by the need to consolidate debt. This is Followed by Credit card loans (5.0K).

- Total Loan Application by Home ownership

![Total Loan by home](https://github.com/user-attachments/assets/b2347e6a-b13a-4f80-a93f-19dca8b73974)

The chart shows the distribution of loan applicants based on the applicant's home ownership status. The largest segment represents individuals who rent their homes with 18.439 loan applications, this suggests that a significant portion of loan applicants are renters. The number of loan applications from homeowners (2,838) and those with mortgages (17,198) are lower compared to renters. This may be due to their finacial needs or the need to improve their credit history.


# Insights



# Recommendation






#
Conclusion
