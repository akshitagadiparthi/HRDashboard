# HRDashboard
![image]




## **Link to the Project**
https://public.tableau.com/app/profile/akshita.gadiparthi2602/viz/HRAttritionDashboard_17391464788680/viz

---

## **Table of Contents**
1. Project Description
2. Technologies Used
3. Features 

---

## **1. Project Description**

**The **HR Attrition Dashboard** is an interactive and data-driven visualization tool designed to track employee attrition trends within an organization. It provides key insights into workforce retention by analyzing attrition rates across various dimensions such as department, job role, demographics, education, and satisfaction scores. The dashboard allows HR teams to identify trends, problem areas, and factors contributing to employee turnover, enabling data-driven decision-making for improving retention strategies.**

---

## **2. Technologies Used**
- **Tableau**: For data visualization and dashboard creation.
- **SQL**: To query and prepare data for analysis.
- **CSV/Excel**: Data sources were imported from these formats.
- **GitHub**: For version control and repository hosting.

---

## **3. Features**
**Overview Metrics – Summary of attrition rate, total attrition, and current employees.**
**Department-wise Attrition – Highlights turnover across different departments.**
**Job Role Analysis – Identifies top roles with the highest attrition.**
**Attrition Trend Analysis – Tracks attrition patterns over time.**
**Demographics Insights – Breaks down attrition by gender, age, and education.**
**Survey Score Analysis – Evaluates employee satisfaction across key factors.**
**Recent Attrition Details – Shows attrition data for individual employees.**
**Interactive Features – Includes filters and tools for customized analysis.**


- **Overview Metrics** 
This section provides a high-level summary of attrition statistics to give a quick understanding of workforce trends.

Components & Purpose:
  Attrition Rate (16.1%)
  -Calculates the percentage of employees who have left the company.
  -Helps HR teams assess how serious attrition is.
  
  Total Attrition (237)
  -Shows the exact number of employees who left within the selected time frame.
  -Helps measure the scope of the issue.
  
  Current Employees (1,233)
  -Displays the total number of employees remaining.
  -Provides context for attrition relative to workforce size.

-**Department-wise Attrition**
This section breaks down attrition by department, helping HR teams understand which departments are losing the most employees.

Components & Purpose:
  R&D (133 left out of 828 total)
  -Sales (92 left out of 354 total)
  -HR (12 left out of 51 total)
  
  Visual Representation:
  -Each department has a circular bar chart showing:
                  -Total employees (black bar)
                  -Attrition count (orange bar)
  
  This makes it easy to compare attrition across departments. Helps identify problematic departments with high turnover and enables the HR to focus retention efforts on specific teams.
  
  **Job Role Analysis**
This section highlights which job roles have the highest attrition rates, helping HR understand which positions are most at risk. This shows which roles experience high turnover and helps HR identify positions that need better retention strategies.

Components & Purpose:
  Top 5 Job Roles with Highest Attrition:
      Laboratory Technician: 62 left (out of 197 total)
      Sales Executive: 57 left (out of 269 total)
      Research Scientist: 47 left (out of 245 total)
      Sales Representative: 33 left (out of 50 total)
      Human Resources: 12 left (out of 40 total)

 **Attrition Trend Analysis (Graph)**
This section tracks how attrition changes over time, helping HR teams spot patterns and predict future trends.Helps HR teams predict future attrition trends. Allows HR to correlate attrition spikes with company events (e.g., layoffs, policy changes).

Components & Purpose:
  Bar chart showing monthly attrition from May 2021 to May 2022.
  Key Insight: Attrition increased significantly from March 2022 to May 2022.
  85.5% drop in attrition from the previous month (indicating improvement).

**Demographics Analysis**

This section analyzes gender, age, and education level to understand who is leaving the company. .

Components & Purpose:
  Gender-wise Attrition- Helps HR identify if attrition is higher for a specific gender
      Male: 150 attritions (out of 732 total males)
      Female: 87 attritions (out of 501 total females)
    Age Group Breakdown- Helps HR tailor retention strategies based on career stages.
      <25 years: 59 left
      25-34 years: 442 left
      35-44 years: 454 left (highest attrition group)
      45-55 years: 239 left
      >55 years: 39 left
    Education Level Breakdown-Helps HR understand if education level influences attrition. Could suggest that employees with higher education levels are less likely to leave.
      Bachelor’s Degree (99 left)
      Master’s Degree (58 left)
      Associate’s Degree (44 left)
      High School (31 left)
      Doctoral Degree (5 left)

**Survey Score Analysis**
This section analyzes employee feedback from workplace surveys to understand how satisfaction affects attrition.Scores are color-coded from 1 (low) to 4 (high). Identifies workplace issues that contribute to attrition. HR can improve employee experience based on this data.

Components & Purpose:
    5 Key Survey Metrics:
        Environment Satisfaction
        Job Satisfaction
        Job Involvement
        Relationship Satisfaction
        Work-Life Balance

**Recent Attrition Details**
This section shows details of recent employees who left, allowing HR to investigate specific cases. Helps HR analyze specific cases of attrition. Identifies if low satisfaction scores or salary hikes impact attrition.

Components & Purpose:
    Example Employee:
      E_780 (Research Scientist, R&D)    
      Attrition Date: 8 May 2022
      Satisfaction Score: 3.2
      Performance Rating: 3
      Monthly Income: $2,686
      Salary Hike: 13%
      
**Interactive Features**
The dashboard allows HR professionals to filter and explore data dynamically. Provides Customization & Flexibility – HR teams can drill down into specific issues based on what they want to analyze.

Components & Purpose:
  **"Show Only Attrition" Toggle**- Filters out retention data to focus solely on employees who left.
 **Click Data Points to Filter Dashboard**- Clicking on age groups, job roles, or departments updates the entire dashboard.
  **Dropdown Filters (EMP ID, Attrition Date)**- Allows HR to search for specific employees.



