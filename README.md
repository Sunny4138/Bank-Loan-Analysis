# Bank Loan   Analysis Report

## Problem Statement

This Power BI dashboard helps banks and financial analysts evaluate loan performance and borrower behavior through interactive visualizations and key performance metrics.  
It provides insights into total loan applications, funded amounts, repayments received, average interest rates, and debt-to-income (DTI) ratios.  
By comparing Good vs. Bad Loans, the report identifies potential risk factors and supports data-driven lending decisions.  
Additionally, regional, term-wise, and borrower-type analyses enable deeper exploration of trends for strategic business improvement.

Since 13.8% of loans are underperforming while 86.2% are performing well, thus the bank should focus on enhancing its credit assessment and loan recovery strategies to improve overall portfolio quality. Also, since metrics such as average interest rate and debt-to-income ratio are closely monitored, thus refining lending criteria and borrower risk assessment can help reduce default risk and increase profitability.

---

## Steps Followed

1. Load data into Power BI Desktop, dataset is a csv file.  
    

2. Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.  
    

3. Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset.  
    

4. Created KPI cards for key metrics like applications, funding, repayments, interest rate, and DTI ratio. 




5. Added slicers and filters (State, Grade, Purpose) for interactive exploration. 



  

6. Built Good vs. Bad Loan analysis segments for applications, amounts, and ratios. 

 
 

 

7. Designed a status grid to display totals for Current, Charged Off, and Fully Paid loans. 


 
  


8. Developed charts for monthly trends, regional analysis, loan terms, employee length, loan purpose, and home ownership.  






9. Added a detailed table view for granular borrower and loan details.  






10. Created calculated columns and DAX measures (Age Groups, Count of Customers, % of Customers).  

   



## Features

- KPI Cards: Real-time metrics for loan applications, funding, repayments, and DTI.  
- Good vs. Bad Loan Analysis: Visual comparison to assess lending risk. 

- Loan Status Overview: Tabular summary of Current, Charged Off, and Fully Paid loans.  
- Trend & Regional Charts: Monthly growth, state-wise lending distribution, and employment-based trends.  

- Purpose & Ownership Analysis: Loan purpose and home ownership visualized via bar and tree charts.  

- Dynamic Filters: Interactive slicers for State, Grade, and Purpose.  
- Drillthrough Table: In-depth data view for each loan and borrower profile.  

---

## Insights

- Loan Applications: Displays monthly and overall application/funding counts.  
- Good Loan Ratio: 86.2% of loans classified as good; 13.8% as bad.  
- Regional Analysis: Identifies states with the highest and lowest lending activities.  
- Loan Status Breakdown: Visualizes Current, Charged Off, and Fully Paid ratios for risk assessment.  
- Interest Rate & DTI: Tracks monthly and overall averages for performance evaluation.  
- Demographic Segmentation: Analyzes loan patterns based on employee length and home ownership.  
- Purpose Segmentation: Highlights dominant loan purposes for business strategy.  
- Details Grid: Centralized view of all key metrics with applied filters.  

---

## Technologies Used

- Power BI (Desktop & Service) – Dashboard creation and publishing  
- MS SQL Server – Data querying and modeling  
- Power Query – Data cleaning and transformation  
- DAX – KPIs, measures, and calculated columns  
- Microsoft Excel – Supporting data validation and testing  

---

## Report Snapshots

- Interactive pages for Summary, Overview, and Detailed Analysis.  
- Visual KPIs, filters, drillthroughs, and multiple chart types (bar, line, map, tree).  
- Quick navigation designed for both business and operational decision-making.  



## Conclusion
This project demonstrates the ability to perform end to end data analysis  from cleaning and transformation to visualization and business insights.  
It helps financial institutions monitor loan portfolios assess borrower risk and make informed lending decisions.
