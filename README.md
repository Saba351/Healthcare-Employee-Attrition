# Healthcare-Employee-Attrition
Healthcare Employee Attrition Analysis (SQL + Tableau)
# 📊 Healthcare Employee Attrition Analysis (SQL + BigQuery)

This project explores employee attrition in a healthcare organization using SQL and Tableau. The goal is to identify key factors contributing to employee turnover and highlight high-risk groups that need HR attention.

---

## 🔍 Key Insights & Observations

### 1. Income Group vs Attrition
- ✅ lower-income employees are leaving at a much higher rate. Attrition drops steadily as income increases.

### 2. Overtime vs Attrition
- ✅ Employees working overtime have an attrition rate almost 6x higher than those who don’t.
-  This shows overtime is a major risk factor for employee burnout and resignation in healthcare.
-  Working overtime nearly triples the attrition risk.

### 3. Job Satisfaction vs Attrition
- There’s a clear negative correlation between job satisfaction and attrition rate.
- Employees with very low satisfaction (Level 1) have nearly double the attrition compared to those with high satisfaction (Level 4).
- This highlights the importance of employee engagement and morale in reducing turnover in the healthcare workforce.

### 4. Age Group vs Attrition
- ✅ Younger employees are more likely to leave.

### 5. Overtime + Low Income Segment
- **Employees with Overtime & Monthly Income < 1000:** 63.7% attrition rate
- ⚠️ This is the highest-risk group and needs urgent HR focus.

---

## 🧰 Tools Used
- **SQL (BigQuery)** – for data querying and calculations
- **Tableau** – for interactive visualizations

---

## 📁 Repository Contents
- SQL query scripts used for analysis
- Tableau screenshots for visual insights

---
## 📷 SQL Query & Dashboard Screenshots

### 1. Income Group vs Attrition
![Income Group vs Attrition](images/income_vs_attrition.png

![Overtime vs Attrition](overtime%20vs%20attrition.png)
![Job Satisfaction vs Attrition](jobsatisfaction%20vs%20attrition.png)
![Age Group vs Attrition](attrition%20by%20age.png)
![Attrition: Overtime & Low Income](attrition%20where%20overtime%20and%20low%20income.png)


### 📊 Tableau Dashboard
![Attrition Dashboard](images/tableau_dashboard.png)

---

## ✅ Recommendations to Reduce Attrition

Based on the analysis, here are actionable suggestions to help reduce employee attrition in the healthcare sector:

- **Improve Compensation for Low-Income Employees:**  
  A large portion of attrition comes from employees earning less than 2000 per month. Offering competitive pay or bonuses may help retain this segment.

- **Address Overtime Burden:**  
  Employees working overtime — especially those with low income — show an attrition rate over 60%. Reviewing shift schedules and reducing excessive workloads is critical.

- **Enhance Job Satisfaction:**  
  Employees with the lowest job satisfaction scores are much more likely to leave. Conduct regular feedback sessions and improve working conditions, recognition programs, and career growth paths.

- **Focus on Younger Workforce:**  
  Employees under 30 have the highest attrition rate. Providing mentorship, training, and growth opportunities can help retain younger talent.

- **Target High-Risk Groups Proactively:**  
  Combine factors (e.g., overtime + low income) to identify and support employees most likely to leave before attrition happens.




