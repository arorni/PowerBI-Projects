# Loan Analysis Power BI Dashboards

## Overview
This Power BI project provides a detailed analysis of bank loan data, focusing on profitability, risks, and loan performance across various dimensions. It is designed to help stakeholders make data-driven decisions by exploring trends, 
identifying key drivers of profitability and loss, and managing loan risks effectively.

### Steps Followed

1. **Data Loading**: Imported bank loans data from a CSV file into Power BI Desktop.
2. **Data Cleaning**: 
   - Enabled “Column Distribution,” “Column Quality,” and “Column Profile” for a detailed overview.
   - A few null values were found in the employee title. Not planning to include it for further analysis.
3. **Data Transformation**: 
   - Created new calculated columns such as Loan Risk, IsVerified etc.
   - Grouped loan_status to different categories: Charged off loans have been assigned to Bad Loans and Currently Active and Fully Paid Loans have been assigned to Good Loans category.
   - Lookup table has been created for state code to state name.
   - Loan grades A, B, and C have been assigned to the Low Risk Loans and others have been assigned to the high risk category.
4. **Visualization Design**: 
   - Slicers have been used for State, Grade, Purpose, and Good/Bad Loans.
   - Measure has been created and used as a slicer to dynamically interact with the BANK LOANS OVERVIEW dashboard.
   - Added KPI visuals to highlight key metrics such as Total Loan Applications, Total Profit, Total Loss, Avg Interest Rate, and Avg Debt/Income ratio for the customers.
   - Designed Donut charts, line charts, stacked bar charts, and tables to illustrate trends in loan applications with each month etc.
   - Page Navigation buttons have been added to switch to different pages.
   
5. **Theme and Branding**: Used a background to enhance the visual appeal.

## Features & Insights
### 1. **Loan Summary Dashboard**
   - Loan summary dashboard shows overall summary about total number of applications received by the bank, Total Profit, Total Loss, Avg Interest Rate, and Avg Debt/Income Ratio.
   - It also reflects total good and the bad loans applications accepted by the bank, amount founded, and amount received by the bank.
   - It also gives detailed overview of different types of loans and the relevant matrix in the tabular form.
### 2. **Loan Distribution & Trends Dashboard**
   - Along with the KPI's on the Bank Loan Summary, It provides us overall trends in the total loan applications, total funded amount, and total amount received (depending upon the measure selected).
   - It shows different characteristics of the customers such as purpose, their home ownership status, term for which they applied, state, and since how long they have been working.
   - Along with different visualizations to get an insights about customer profile, slicer for state, grade, and good/bad loans have been provided to understand different aspects.
### 3. **Loan Analysis Dashboard**
   - Along with all the KPIs, it highlights bank's distrubution of bad loans and how many of them were from high/low risk category customers and their home ownership status.
   - Highlights the status of verification for all the loan applications within the high/low risk loans and total amount received from high and low risk loans.

### 4. **Bank Loan Details Dashboard**
   - Along with all the KPIs, it shows some of the important fields in the tabular format.

## Important Findings/Insights
- Despite generating $35.4M in profit, bad loans have led to $29.8M in losses, emphasizing the need for stricter risk management.
- Surprisingly, numbers of bad loans are more in Low risk loan categories. It seems the loans given to the low risk category customers
  have not been verified properly. 
- Customers who own their house tend to default less as compared to others.
- Total number of application accepted from the low risk customers have been increased over time.

## Suggestions
- Bank should be more strict about verifying its customers.
- Over time, bank has increased it's emphasis on accepting low risk applications. It should continue doing that and it should give more preference to the customers who own their house.

## Data Sources
- Dataset used has been given in the github repo for this project.

## Usage Instructions
1. **Open the PBIX File:** Load the `Loan_analysis.pbix` file in Power BI Desktop.
2. **Navigate Through Dashboards:** Use the navigation pane to explore insights in each dashboard.
3. **Apply Filters:** Adjust filters for loan type, home ownership, risk levels, and other dimensions to uncover deeper insights.
4. **Export Reports:** Export visuals or entire dashboards to share findings in PDF or Excel formats.

