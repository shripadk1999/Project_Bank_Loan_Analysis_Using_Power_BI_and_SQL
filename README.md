# Project Bank Loan Analysis Using SQL and Power BI

## Objective:
The objective of this project is to analyse the historical debt record of a bank and provide actionable insights through a dashboard for checking overall health and profitability of a bank. These  insights will prove helpful for the Credit Risk Assessment Team for their further analysis.
Throughout this project, I've had the chance to:<br />
  1.Dive deep into the study of the banking domain to uncover valuable insights. <br />
  2.Develop interactive dashboards to visualise key banking and finance metrics.<br />
  3.Provide data-driven recommendations for strategic decision-making.

## Steps Followed:
### 1. Data Gathering:
Importing raw data .csv file into Power BI & transform to Power Query editor for cleaning and data processing.
### 2. Data cleaning:
Cleaning is done by removing empty columns, removing duplicates, errors etc.<br />
Replacing values in column with proper values and naming.
Detecting data type of every column, using the auto detect data type function in Power query editor and performing manual cross check.
### 3. Data processing:
* At initial stage, KPIs were identified using SQL in SQL Server Management Studio to prevent any miscalculations in Power Query Editor<br />
* In the Power Query editor, a new table called "Date Table" was created  by using the DAX expression.Further new measures were created under this table such as Total Loan Applications, Total Funded Amount, Total Amount Received, Average DTI and Average Interest Rate.<br />
* Further, Complex measures were created using Time Intelligence Functions: Previous-Month-To-Date, Month-To-Date values and Month-On-Month change (in %) were calculated for all the above primary measures.<br />
In the DAX Query view, “Select Measure” named table was also included.<br />
### 4. Data Modelling:
 In Model View, One to Many relationships were established between dimension tables and fact tables. For this Star Schema is used.
### 5. Data Analysis:
* Analysis involves the creation of a range of visual representations, including bar charts, key performance indicators (KPIs), table charts, area charts, donut & pie charts,line charts and other relevant visualisations.<br />
* These tools are utilised to gain insights and present data in a comprehensive and easily understandable manner.

## Key Questions of The Dashboard:
* What are the Total Loan Applications, Total Funded Amount, Total Amount Received, Average DTI and Average Interest Rate?<br />
* What is the distribution of Good and Bad Loans?<br />
* What is the distribution of Loans as per Loan Status?<br />
* What is the distribution of Total Amount Received as per Employment Length of any employee?<br />
* What is the distribution of Total Loan Application by Purpose?<br />
* State wise map-based distribution of Total Amount Received for USA <br />

## Learned About: 
* Calculated Fields <br />
* DAX Measures  <br />
* Tree Map And Geographical Map  <br />
* Donut chart and Area Chart<br />
* Bar Chart and Cluster chart 📊<br />
* KPI(Key Performance Indicators) and Slicer.<br />
* Filters: Used to filter data according to different City and Brands.<br />
* Time Intelligence Functions <br />

## Key Insights Summary:
* Analysed historical debt records of a bank using SQL Server Management Studio and Power BI with following insights:<br />
* The bank is in a healthy state as it has managed to settle for a net profit of 8.55%.But as 13.8% are  Bad Loans, the bank needs to revisit its credit risk assessment strategy. <br />
* Average Debt-to-Income ratio is highest for Current Loans(14.72%) as compared to Fully paid (13.17%) and Charged Off (14%) loans <br />
* California is the state with highest Total Amount Received ($83 mn) <br />
* Employee with 10+ years of employment have contributed maximum to loan repayment($126 mn) <br />
* Largest loan is taken for Debt Consolidation ($254 mn ) by households <br />
* Maximum loan applicants have Rented or Mortgaged Home (67%) <br />
## Dashboards:
![PBI Bank Loan Report 1](https://github.com/shripadk1999/Project_Bank_Loan_Analysis_Using_Power_BI/assets/161477229/a822b20b-2ea7-4821-84b8-3b9d4fa51502)
![PBI Bank Loan Report 2](https://github.com/shripadk1999/Project_Bank_Loan_Analysis_Using_Power_BI/assets/161477229/1b36c4f8-7847-4901-a431-6bc775445ada)
![PBI Bank Loan Report 3](https://github.com/shripadk1999/Project_Bank_Loan_Analysis_Using_Power_BI/assets/161477229/0becadac-f240-4610-af74-855684689799)
