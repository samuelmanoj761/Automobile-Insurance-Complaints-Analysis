# Automobile-Insurance-Complaints-Analysis
Analysis of automobile insurance complaints, company performance, and premium trends using SQL and Power BI.

**DataMites Client Project | CDACL-001**

### Project Overview

This project focuses on analyzing automobile insurance complaints reported against insurance companies operating in New York State between 2009 and 2016.

I used SQL for data exploration and Power BI to analyze complaint trends, company performance, complaint outcomes, and premium changes. The goal was to understand complaint patterns and identify areas where insurance companies could improve their complaint-handling processes.

### Tools Used

- **SQL / phpMyAdmin** — Database exploration and queries
- **Power Query** — Data preparation
- **Power BI** — Data analysis, DAX measures, and interactive dashboards
- **Microsoft Word** — Analysis report and recommendations
- **PowerPoint** — Project presentation

### Dataset Overview

The dataset includes insurance company information, complaint counts, complaint ratios, premium amounts, and company rankings.

**Key fields:** Company_Name, NAIC, Filing_Year, Total_Complaints, Upheld_Complaints, Not_Upheld_Complaints, Question_of_Fact_Complaints, Premiums_Written, Ratio, and Ranking.

### Dashboard Highlights

The overall insurance complaints dashboard provides:

- **35,919** total complaints
- **223** insurance companies
- **4,216** upheld complaints
- **0.0164** median complaint ratio
- Year-wise complaint trends
- Complaint outcome distribution
- Comparison of five insurance companies

### Company Complaint Analysis

I selected **Allstate Insurance Company** for a closer analysis of its complaint history.

**Key Findings:**

- Total complaints: **4,949**
- Upheld complaints: **760**
- Not upheld complaints: **2,301**
- Question of Fact complaints: **1,888**
- Highest yearly complaints: **1,350 in 2010**
- Complaints in 2016: **237**

The analysis shows a significant decline in recorded complaints over the study period. However, complaint volumes alone do not confirm changes in customer satisfaction.

### Premium Trend Analysis

Allstate's reported premium values showed a declining trend between 2009 and 2016.

- **2009:** Approximately $1,269.44 million
- **2016:** Approximately $747.43 million
- **Change:** Approximately 41.1% decrease

The dataset measures premiums as the average of the current and previous year's premiums written in New York State.

Changes in policy volume, competition, pricing decisions, and market conditions could influence premium trends. Further information would be needed to identify the actual causes.

### Five-Company Comparison

The dashboard compares complaint volumes across:

1. Allstate Insurance Company
2. GEICO General Insurance Company
3. Country-Wide Insurance Company
4. State Farm Mutual Automobile Insurance Company
5. GEICO Indemnity Company

This comparison helps highlight differences in complaint volumes. Complaint ratios and business size should also be considered when evaluating company performance.

### Key Recommendations

- Monitor complaint patterns regularly.
- Identify recurring issues behind customer complaints.
- Improve communication during claims and complaint handling.
- Track complaint ratios alongside premium and business performance.
- Review complaint outcomes to identify possible service improvements.

### Project Deliverables

The repository contains the completed project materials:

- Power BI dashboard (`.pbix`)
- Final analysis report (`.pdf`)
- PowerPoint presentation (`.pptx`)
- Supporting documentation, where included

### Conclusion

This project helped me apply SQL and Power BI to a practical insurance analytics problem. I worked with complaint data, explored trends, compared insurance companies, and prepared a dashboard and report to communicate the findings.

The analysis demonstrates how data visualization can support performance monitoring and help identify areas for business improvement.

---

**Project:** CDACL-001 — Automobile Insurance Complaints Rankings

**Tools:** SQL | Power Query | Power BI

**Analysis Period:** 2009–2016

*Dataset provided for the DataMites client project. Original database credentials and restricted source materials are not included in this repository.*
