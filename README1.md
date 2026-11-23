# HR Attrition Analysis Dashboard

An interactive Power BI dashboard that shows **who is leaving, and why**, using HR data of 1,473 employee records.

![HR Dashboard](images/hr-dashboard.png)

## Business Problem
Employee attrition means lost experience and rehiring cost. This project answers:
- What is the overall attrition rate?
- Which age groups, salary bands, departments and education fields lose the most people?
- Where should HR focus to improve retention?

## Dataset
- **Source:** [dataset name / link]
- **Size:** 1,473 employee records, 36 columns
- **Key columns:** age, gender, monthly income, department, education field, job role, overtime, attrition

## Data Preparation (Excel)
- Created age groups (18-25, 26-35, 36-45, 46-55, 55+)
- Created salary slabs (Upto 5k, 5k-10k, 10k-15k, 15k+)
- Created an attrition flag (1 = left, 0 = stayed)
- [Add what else you did: duplicates, data types, blanks]

## Key Metrics
| Metric | Value |
|---|---|
| Total employees | 1,473 |
| Employees who left | 237 |
| Attrition rate | 16.09% |
| Average age | 36.92 |
| Average monthly salary | 6,500 |
| Average tenure | 7.00 years |

## Key Insights
1. **Age:** Employees aged **18-25 had the highest attrition (35.8%)**. The 26-35 group had the most leavers (116) at 19.1%. Attrition fell to 9-11% for ages 36-55.
2. **Salary:** Employees earning **up to 5k left at 21.7%**, against 3.8% for those earning above 15k.
3. **Department:** Sales had the highest attrition (20.6%), then HR (19.0%) and Research & Development (13.8%).
4. **Gender:** Men left at 17.0% and women at 14.8%, so the gap is small.
5. **Education field:** HR (25.9%), Technical Degree (24.2%) and Marketing (22.0%) were highest. The HR group is only 27 people, so read it with care.

## Recommendations
- Review pay for the lowest salary slab (up to 5k), where attrition is highest.
- Focus retention on employees under 35, such as mentoring and career-growth plans.
- Look at workload and role fit in Sales, which has the highest departmental attrition.

## Tools Used
- **Excel:** data cleaning and preparation
- **Power BI:** data modeling and the interactive dashboard

## Repository Structure
```
├── dashboard/   # Power BI (.pbix) file
├── data/        # HR_Cleaned.xlsx
├── images/      # hr-dashboard.png
└── README.md
```