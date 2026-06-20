# HR Analytics Dashboard — Employee Attrition Analysis

## Project Overview

This Excel workbook provides a comprehensive analysis of employee attrition across a workforce of **1,470 employees**. It is designed to help HR and business leaders understand who is leaving, why patterns emerge, and where retention efforts should be focused. The project includes raw employee data, pivot-based summaries, KPI tracking, and segmented attrition breakdowns across multiple dimensions.

---

## Dataset Summary

| Metric | Value |
|---|---|
| Total Employees | 1,470 |
| Active Employees | 1,233 |
| Attrition Count | 237 |
| Attrition Rate | ~16.1% |
| Average Employee Age | ~36.9 years |

---

## Workbook Structure

The file contains the following sheets:

### `HR DATA_Excel.xlsx - Data`
The raw employee-level dataset. Each row represents one employee and includes the following attributes:

- **Demographics:** Age, Gender, Marital Status, Age Band
- **Employment:** Department, Job Role, Job Level, Employee Number
- **Compensation:** Monthly Income, Daily Rate, Hourly Rate, Monthly Rate, Percent Salary Hike, Stock Option Level
- **Work History:** Total Working Years, Years at Company, Years in Current Role, Years Since Last Promotion, Years with Current Manager, Num Companies Worked
- **Satisfaction & Engagement:** Job Satisfaction, Environment Satisfaction, Job Involvement, Relationship Satisfaction, Work-Life Balance
- **Performance:** Performance Rating, Training Times Last Year
- **Travel & Hours:** Business Travel, Over Time, Standard Hours, Distance from Home
- **Education:** Education Level, Education Field
- **Attrition Flags:** Attrition (Yes/No), CF_attrition label, CF_attrition count, CF_current Employee, CF_attrition rate

### `KPI`
Top-level summary metrics for quick executive reporting:
- Total employee headcount
- Total attrition count
- Average employee age
- Active employee count
- Overall attrition rate

### `rating`
Summarises the average job satisfaction score and its proportional balance (rating vs. balance rating), useful for gauging overall workforce sentiment.

### `Gender`
Breakdown of the workforce by gender:
- Female: 588 (40%)
- Male: 882 (60%)

### `Education by attrition`
Attrition counts segmented by highest education level attained:
- Bachelor's Degree accounts for the largest share of attrition (99 employees)
- Doctoral Degree has the lowest attrition (5 employees)

### `attrition by job`
Attrition counts by job role. Key findings:
- Laboratory Technician (62) and Sales Executive (57) are the highest attrition roles
- Research Director (2) and Manager (5) have the lowest attrition

### `attrition by age group`
Attrition segmented by age band:
- The 25–34 age group has by far the highest attrition (112 employees)
- Employees over 55 have the lowest attrition (11 employees)

### `Department wise attrition`
Proportional attrition split across departments:
- R&D: ~56% of all attrition
- Sales: ~39%
- HR: ~5%

### `attrition by marital status`
Employee count by marital status (all employees, not just those who left):
- Married: 673
- Single: 470
- Divorced: 327

### `Sheet2`
Reserved/empty sheet (unused).

---

## Key Analytical Insights

1. **High-risk roles:** Laboratory Technicians and Sales Executives account for nearly half of all departures. Targeted retention initiatives — such as career pathing, compensation reviews, or workload audits — are warranted for these groups.

2. **Age-driven attrition:** The 25–34 cohort is the highest attrition segment by a wide margin, suggesting early-career employees may not be finding sufficient growth opportunities or engagement.

3. **Departmental concentration:** R&D absorbs over half of all attrition. Given the specialised nature of R&D roles, the cost of replacement is likely high; this department merits priority HR attention.

4. **Education paradox:** Employees with Bachelor's degrees leave at higher rates than those with advanced or doctoral qualifications, which may reflect compensation misalignment or greater external market demand for this group.

5. **Satisfaction baseline:** The average job satisfaction score of ~2.6 out of 5 indicates moderate dissatisfaction across the workforce, which likely contributes to the 16% attrition rate.

---

## How to Use This Workbook

1. **Start with the KPI sheet** for an at-a-glance health check of the workforce.
2. **Use the segmented sheets** (job, age group, department, education) to drill into where attrition is concentrated.
3. **Reference the raw data sheet** to build additional pivot tables or apply filters for ad-hoc analysis.
4. **Use the rating sheet** to monitor satisfaction trends over time as a leading indicator of future attrition risk.

---

## Dashboard

![Overview](screenshot72.png)

---

## File Details

| Property | Value |
|---|---|
| File Name | `Excel_project_complete.xlsx` |
| Format | Microsoft Excel (.xlsx) |
| Number of Sheets | 10 |
| Primary Data Rows | 1,470 employees |
| Number of Columns (raw data) | 44 |
