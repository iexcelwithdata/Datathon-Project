# Early-Warning Analytics System for Student Performance Risk

## Executive Overview

This project was developed during **DataFest Africa Hackathon 2024** to address a critical question in secondary education:

> **How can schools identify students at risk of academic failure early enough to intervene — using data rather than intuition?**

Using a realistic, simulated school dataset, this project delivers an **early-warning analytics system** that combines **data engineering, predictive analytics, and business intelligence** to support proactive academic decision-making.

Rather than optimizing for model accuracy alone, the solution emphasizes **interpretability, intervention timing, and operational usability** for educators and administrators.

**Key outcomes**
- Predictive risk classification model for pass/fail outcomes  
- End-to-end analytics pipeline from ingestion to reporting  
- Identification of non-academic drivers of performance (attendance, assessment frequency)  
- Approximately **60% reduction** in manual reporting effort  

---

## Problem Context

Academic underperformance in many secondary schools is addressed **after** final exam results are released.  
This reactive approach limits the effectiveness of remediation efforts.

Key challenges include:
- Fragmented student performance data  
- Limited early indicators of academic risk  
- Minimal visibility into non-academic performance drivers  

This project focuses on building a **data-driven early-warning system** that enables timely, targeted interventions.

---

## Solution Overview

The solution is designed around **decision support**, not dashboards alone.

### Core Objectives
- Identify students at risk of failing before exams  
- Surface actionable drivers of underperformance  
- Enable data-informed academic interventions  

---

## Data Architecture & Pipeline

The system follows a production-style analytics workflow:

1. **Data Generation**
   - Simulated student data reflecting real-world school environments  
   - Academic scores, attendance records, assessment frequency, and contextual attributes  

2. **Data Engineering**
   - Automated ingestion using **Airbyte**  
   - Data transformation and modeling with **dbt**  
   - Centralized storage in **BigQuery**

3. **Data Modeling**
   - Relational models linking students, performance, and engagement indicators  
   - Features designed for interpretability and stability  

4. **Analytics & Reporting**
   - Executive-ready dashboards built in **Power BI**  
   - Focus on early intervention and resource prioritization  

---

## Predictive Analytics Approach

The predictive model was built to support **operational decisions**, not just statistical evaluation.

Key considerations:
- Clear separation between risk classes  
- Stability across student cohorts  
- Transparent feature contribution  

Key findings:
- Attendance consistency is a stronger predictor than raw academic scores  
- Frequent internal assessments significantly increase pass likelihood  
- Predictive insights are most effective when paired with defined intervention rules  

---

## Key Insights & Impact

| Insight | Practical Implication |
|------|----------------------|
| Attendance strongly predicts failure risk | Early attendance-based intervention |
| Regular mock tests improve outcomes | Policy changes around assessment frequency |
| Risk clusters remain stable over time | Targeted mentorship and academic support |
| Automated reporting reduced admin workload | Scalable monitoring across classes |

---

## Dashboard & Reporting

The Power BI dashboard is designed for **non-technical stakeholders**, enabling:
- Monitoring of at-risk students  
- Cohort and class-level performance analysis  
- Drill-down by subject and contributing factors  

### Dashboard Preview
![Dashboard Preview](./Images/Datathon.png)

[View Full Dashboard (PDF)](./DataFest%20Project%20Dashboard.pdf)

---

## Competition Result

This project placed **7th out of 100+ teams** at the **DataFest Africa Hackathon 2024**, based on:
- Technical execution  
- Business relevance  
- Real-world applicability  

---

## Limitations & Future Work

Planned enhancements include:
- Integration with real-time school management systems  
- Temporal modeling for tracking risk progression  
- API deployment for continuous prediction updates  
- Structured intervention playbooks for educators  

---

## Why This Project Matters

This project demonstrates the ability to:
- Design analytics systems around **decisions**, not tools  
- Integrate data engineering, analytics, and BI into a cohesive solution  
- Translate predictive insights into operational outcomes  

The framework generalizes to domains such as:
- Customer churn prevention  
- Credit risk monitoring  
- Workforce attrition analytics  
- Healthcare early-warning systems  

---

## Author

**Kuku Faruq Olabiyi**  
_Data Analytics | Business Intelligence | Data Engineering_

- Email: kukuolabiyi04@gmail.com  
- LinkedIn: https://www.linkedin.com/in/faruqkukuolabiyi  
- GitHub: https://github.com/iexcelwithdata  
