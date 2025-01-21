
# HR Analytics Dashboard

## Problem Statement

The HR Analytics Dashboard provides actionable insights into workforce data, helping organizations make informed decisions to improve employee retention, performance, and satisfaction. It enables HR professionals to identify key trends, areas of improvement, and opportunities to enhance workplace efficiency. The dashboard showcases metrics such as attrition rates and satisfaction levels, empowering organizations to develop targeted strategies to address challenges.

With this dashboard, HR teams can understand:
- What is the current attrition rate and the primary characteristics of the employees who are leaving the company.
- Which departments or job roles require immediate attention?


By leveraging these insights, organizations can enhance workforce planning and build a stronger, more satisfied workforce.

---

### Steps Followed

1. **Data Loading**: Imported workforce-related data from a CSV file into Power BI Desktop.
2. **Data Cleaning**: 
   - Used Power Query to inspect and clean data.
   - Enabled “Column Distribution,” “Column Quality,” and “Column Profile” for a detailed overview.
   - Applied column profiling to the entire dataset for consistency.
   - Addressed null/error values and removed unnecessary columns.
3. **Data Transformation**: 
   - Created new calculated columns for metrics such as attrition count using DAX expressions.
   - Grouped employees into age brackets.
4. **Visualization Design**: 
   - Used slicers for each department to allow dynamic filtering.
   - Added KPI visuals to highlight key metrics such as attrition rate, average tenure, average salary and average age of employees.
   - Designed bar charts, pie charts, and line graphs to illustrate trends in attrition w.r.t age, education, salary, job role, and gender.
5. **Theme and Branding**: Used a background to enhance the visual appeal.


---

### Key Features

- **Attrition Analysis**: Understand the factors contributing to employee turnover and identify high-risk segments.
- **Performance Tracking**: Visualize trends in employee performance across departments and job roles.
- **Satisfaction Insights**: Evaluate employee satisfaction scores and pinpoint areas needing improvement.
- **Interactive Filters**: Explore data dynamically with filters for department, job role, and employee demographics.
- **KPI Metrics**: Monitor critical HR metrics like average tenure, satisfaction rate, and attrition percentage.

---

### Insights

1. **Attrition Trends**: 
   - Highest attrition has been observed in Research and Development department with attrition rate of 13.8%.
   - Approximately 65% of workforce is in Reserch and Development department. Around 83% of those who left the company
     were earning up 5K. 
   - In R&D department, Laboratory Technician and Reserch Scientist are the two top most roles among churners. These roles also
     stand out among the people who were not satisfied with the company and gave a rating of 1 in the satisfaction survey.  
   - Employees with in the age group of 26-35 are more likely to leave the company then other age groups. 
   

2. **Satisfaction Insights**:
   - With satisfaction rating, company can take more elaborative response from the employee and analyze that unstructured data to
     get further insights and improve the retention rate.

3. **Demographic Trends**:
   - Age Group Distribution: 
     - Employees with in the age group of 25-35 are the most frequently hired and have the highest attrition rates 
     - Attrition rate decreases with age. 
   - Gender Distribution:
     - [64%] male, [36%] female

---

### Additional Details

- **Data Sources**: The dataset includes employee records, performance reviews, and satisfaction survey results.
- **Calculated Columns**:
  - AttritionCount: AttritionCount column created to assign a binary value (i.e., 0/1) based on the attrition status.
- **Measures**:
  - AttritionRate: Calculated using `SUM` and `DIVIDE` for percentage representation.

---

## Screenshots
![Dashboard Screenshot](https://github.com/arorni/PowerBI-Projects/tree/main/HR%20Analytics%20Dashboard/HR_Analytics_Dashboard.jpg)

---

### Publish and Share

I don't have access to the Power BI service. This dashboard can be published to Power BI Service to allow secure sharing and real-time updates for stakeholders.


