# 🧑‍💼 Human Resources Role and Type Analysis — Power BI Project

![Task 34B](https://github.com/user-attachments/assets/00f3015d-854d-49c4-8c83-455592a51787)


## 📌 Executive Summary

This project delivers a deep dive into workforce composition using Microsoft Power BI. It explores patterns in employee roles, demographics, classification, and performance to guide strategic HR decisions on retention, hiring, and organizational development.

The analysis is based on **1,533 employee records** spanning **26 features**, covering the company's journey from a 65-employee startup to a 1,000+ employee tech-driven firm.

---

## 🎯 Project Objectives

- Understand employee status, roles, and performance metrics
- Identify termination trends and workforce churn patterns
- Analyze demographic diversity and departmental structures
- Deliver insights via interactive Power BI dashboards

---

## 📂 Data Overview

- **Records**: 1,533
- **Columns**: 26
- **Source**: Internal HR lifecycle database (Downloaded from Kaggle)
- **Scope**: Active and former employees across all U.S. states
- **Tool**: Microsoft Power BI
- **ETL Process**: Conducted in **Power Query**
- **Skills Applied**: Power BI, Power Query, DAX, Data modeling, Storytelling

---

## 🧱 Dataset Structure

### ➕ Independent Variables

- Employee ID, Name, Supervisor, Department
- Employee Type (Full-time, Part-time, Contract)
- Job Title, Business Unit, Pay Zone
- Location, Gender, Race, Marital Status

### ➖ Dependent Variables

- Start/Exit Dates
- Termination Types
- Employee Status
- Performance Ratings

---

## 🔧 Data Preprocessing & Techniques

- ✅ Cleaned duplicates and invalid entries
- 🔄 Standardized job titles and departments
- 🧠 Created DAX measures for monthly trends (`FORMAT([Date], "mmm")`)
- ⚙️ Encoded exit reasons and structured status categories
- 🧪 Enabled dynamic filtering with slicers and report-level filters

---

## ❓ Key Questions

- Who are the top-performing employees?
- Which departments face the highest attrition?
- What times of year see the most exits?
- Which roles align with long tenure or high turnover?
- Do performance ratings vary across pay zones and job types?

---

## 📈 Key Insights & Trends

| Metric | Insight |
|-------|---------|
| 🏢 Growth | From 65 to 1,000+ employees |
| 💼 Status | Full-Time (64.83%), Part-Time (31.64%), Contract (33.53%) |
| 📉 Churn | Summer months (June–August) show peak exits |
| 🧑‍💻 High Turnover | Production & Contract employees |
| 📊 Avg Rating | 2.95 – 3.02 (Stable over time) |

---

## 📊 Power BI Visuals & Metrics

![Task 34B](https://github.com/user-attachments/assets/a37fbece-ace0-46eb-95a2-fac80410d48b)


- **Employee Status**: Full-time, part-time, and contract overview
- **Pay Zones**: Compensation bands by job type
- **Performance Ratings**: Bell curve across departments
- **Monthly Exits**: Seasonality visualized using month abbreviations (`"mmm"`)
- **Department Sizes**: Production, IT, Sales, Engineering, Admin, Exec
- **Race/Ethnicity**: Broad representation across groups
- **Job Title Frequency**: Top roles visualized

---

## ✅ Recommendations

- 🧭 **Remote-Friendly Onboarding**: Improve integration for new hires  
- 📚 **Upskill Workers**: Focus on production-to-tech role transitions  
- 🔄 **Convert Contractors**: Long-term retention and cost savings  
- 📅 **Monthly Reviews**: Continuous feedback for engagement  
- 🌍 **Diversity & Inclusion**: Strengthen ERGs, mentorship, and hiring equity  
- 📤 **Standardize Exit Interviews**: Uncover patterns behind turnover  
- 🌞 **Address Summer Attrition**: Offer bonuses, flexible options  
- 📊 **Predictive Modeling**: Use DAX to proactively flag churn risks  

---

## 🧾 Conclusion

This analysis demonstrates how Power BI can uncover actionable insights in workforce data. From department-level attrition patterns to performance consistency and diversity metrics, it enables HR leaders to make evidence-based decisions and improve employee experience.

### ✅ Strengths

- Diverse workforce and locations  
- Stable performance trends  
- Clear role classifications and compensation structure  

### ⚠️ Challenges

- High summer exits  
- Contractor churn  
- Inconsistent retention across teams  

---

## 📚 References & Tools

- **Data Source**: Internal HR & Employee Records  
- **ETL Tool**: Power Query in Microsoft Power BI  
- **BI Tool**: Microsoft Power BI  
- **Languages & Functions**: DAX (e.g., `FORMAT([Date], "mmm")`)  
- **Skills Used**: Data modeling, cleaning, dashboard creation, storytelling  

---

## 📎 Appendices

- Termination breakdown by department  
- State-wise employee distribution  
- Performance rating matrix  
- Job title cleaning logic  
