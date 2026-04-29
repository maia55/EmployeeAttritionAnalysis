# Employee Attrition Analysis

## Objective
This project demonstrates Excel proficiency through the analysis of employee turnover patterns to identify key drivers of attrition and inform retention strategies.

## Tools 
Microsoft Excel (Data Cleaning, Pivot Tables, Data Visualization) 

## Dataset 
- IBM HR Analytics Employee Attrition Dataset via Kaggle
  
### Data Cleaning 
- Removed irrelevant columns (e.g. EmployeeNumber, MonthlyRate, StandardHours, etc.)
- Created new columns for an easier analysis:
  - attritionNumeric (1 Yes, 0 No)
  - overTimeNumeric (1 Yes, 0 No)
  - ageGroup (Young, Mid, Experienced)
  - incomeGroup (Low, Medium, High)
  - yearsAtCompanyGroup (New, Mid, Long-term)

## Key Analysis
Used pivot tables to examine attrition across: 

### Attrition Rate by Department <img width="299" height="82" alt="Screenshot 2026-04-28 at 10 25 51 PM" src="https://github.com/user-attachments/assets/0a1021e0-63ef-49ab-a9bf-38859b037e05" />

### Attrition Rate by Job Role <img width="299" height="178" alt="Screenshot 2026-04-28 at 10 27 21 PM" src="https://github.com/user-attachments/assets/b436090a-1266-4e31-a21d-4196f0ca6863" />

### Attrition Rate by Monthly Income <img width="296" height="81" alt="Screenshot 2026-04-28 at 10 27 59 PM" src="https://github.com/user-attachments/assets/1479c362-828f-4925-b1c2-d5f93467b114" />

### Attrition Rate by Overtime <img width="299" height="64" alt="Screenshot 2026-04-28 at 10 28 37 PM" src="https://github.com/user-attachments/assets/a4480b01-9e5c-4184-862e-3e44b6196943" />

### Attrition Rate by Work-Life Balance (1 (Bad) - 4 (Best)) <img width="295" height="93" alt="Screenshot 2026-04-28 at 10 28 51 PM" src="https://github.com/user-attachments/assets/0ee10190-1e79-452b-a698-c43bd7b95246" />

### Attrition Rate by Age Group <img width="293" height="79" alt="Screenshot 2026-04-28 at 10 29 58 PM" src="https://github.com/user-attachments/assets/1f0a0912-1c52-499f-9575-87099d08a788" />

### Attrition Rate by Years at Company <img width="290" height="79" alt="Screenshot 2026-04-28 at 10 30 13 PM" src="https://github.com/user-attachments/assets/7248a399-b54d-45d7-8b45-e0204eba3d0c" />

## Key Insights
- Overtime employees have ~3x higher attrition (30% vs 10%)
- Lower-income employees leave more frequently (~29%)
- Sales Representatives show the highest turnover (~40%)
- New employees (0-2 years) have the highest attrition (~30%)
- Poor work-life balance correlates with higher attrition

## Conclusion
The analysis shows that attrition is influenced by a combination of compensation, workload, tenure, and employee satisfaction factors.

# Dashboard 
<img width="588" height="798" alt="Screenshot 2026-03-27 at 1 12 02 AM" src="https://github.com/user-attachments/assets/bb3d7ff4-4e7d-45bd-8f42-d12df30d72e4" />

# File/Link Included
- Employee Attrition Analysis.xlsx - includes sheets for the original dataset, cleaned dataset, pivot tables, and dashboard. 
- IBM HR Analytics Employee Attrition & Performance: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data 
