# HR Analytics & Employee Attrition Dashboard (Tableau Project)

A comprehensive, interactive **Tableau Analytics Project** designed to track workforce metrics, analyze key drivers of employee turnover, and provide data-driven recommendations to improve retention and employee satisfaction.

## 📊 Project Overview

This project features two high-fidelity dashboard interfaces that consolidate critical human resource data to reveal underlying operational trends:
1. **HR Analytics Dashboard:** Monitors overall workforce health, average monthly incomes, department-wise role comparisons, educational distributions, and job satisfaction ratings.
2. **Employee Attrition Analysis:** Deep-dives into the operational, demographic, and behavioral factors directly influencing employee turnover.

---

## 🔑 Key Metrics Breakdown

* **Total Employees:** 1,470
* **Current Employees:** 1,233
* **Attrition Count:** 237
* **Overall Attrition Rate:** 16.12%
* **Average Monthly Income:** \$6,503

---

## 🖼️ Dashboard Walkthrough & Features

### 1. HR Analytics Dashboard
Monitors structural demographics, satisfaction metrics, and compensation breakdowns across business units.

![HR Analytics Dashboard](screenshots/hr-analysis.png)

* **Department-wise Avg. Income By Job Role:** Breaks down salaries to identify equity gaps; highlights that R&D and Sales Managers command the highest average compensation, while entry-level roles sit significantly lower.
* **Overtime Distribution:** Tracks employee distribution where **28.30%** of the workforce clocks overtime hours, marking a critical indicator for burnout risk assessment.
* **Avg. Job Satisfaction By Department:** Heatmap matrix evaluating satisfaction rankings out of 4 across roles (e.g., HR Managers scoring highest at `2.82`, while lower satisfaction scores flag vulnerable entry-level groups).

### 2. Employee Attrition Analysis
Pinpoints demographic hotspots and organizational variables correlated with employee departures.

![Employee Attrition Analysis](screenshots/employee-attrition.png)

* **Attrition By Department:** **R&D** registers the largest absolute volume of departures (**133 employees**), closely followed by **Sales** (**92 employees**).
* **Attrition By Job Role:** Entry and frontline roles experience the highest turnover intensity, led by **Laboratory Technicians (62)**, **Sales Executives (57)**, and **Research Scientists (47)**.
* **Attrition By Age & Gender Group:** The **25–34 age bracket** experiences the most significant churn, with male employees heavily representing the highest absolute count (69) across all demographics.
* **Attrition Rate By Work-Life Balance:** Correlates directly to retention success. Employees with a **'Poor' work-life balance record an alarming 31.25% attrition rate**, which is more than double the rate of those scoring 'Good' (14.22%).

---

## 💡 Strategic Recommendations

1. **Targeted Interventions for Voted Core Roles:** Deploy proactive career-progression tracking and retention bonuses for high-attrition roles like Laboratory Technicians and Sales Executives.
2. **Work-Life Balance Policy Overhaul:** Introduce flexible scheduling, hybrid options, or project reallocations for departments reporting high overtime hours, directly combating the 31.25% turnover rate seen among overworked employees.
3. **Early-Career Mentorship Initiatives:** Formulate tailored development programs targeted at the vulnerable 25-34 age demographic to build long-term institutional loyalty.

---

## 🛠️ Tech Stack & Instructions

* **Analytics Tool:** Tableau Desktop / Tableau Public
* **Data Sources:** HR Information Systems (HRIS) Excel/CSV Exports

### How to Interact with the Tableau File (`.twbx`):
1. Download the `HR_Analytics_Project.twbx` file from this repository.
2. Open the workbook using **Tableau Desktop** or **Tableau Reader** (Free).
3. Use the top filters (Department, Work-Life Balance, and Age Group) to interactively drill down into localized demographic insights.

---
*"This project serves as an executive roadmap to transform raw HR information into actionable retention strategies, helping organizations foster healthier, more sustainable workplace environments."*
