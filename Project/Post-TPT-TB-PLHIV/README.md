# Post-TPT TB in PLHIV: Characteristics and Time-to-Event (2014–2020)

> Analysis of **tuberculosis (TB)** occurrence among people living with HIV (PLHIV) after completing **TB Preventive Therapy (TPT)**, identifying clinical and behavioral factors linked to post-TPT TB and estimating time-to-TB events in routine program settings.

---

## 👤 Role & Problem Statement
**Role:** *Data Analyst* — responsible for **cohort building**, **descriptive analysis**, and **time-to-event summaries** using EMR-linked datasets.  
**Problem solved:** Quantified **who develops TB post-TPT** and the **timing of recurrence**, supporting targeted interventions for high-risk PLHIV groups.

---

## 🧰 Languages, Utilities & Statistical Methods

<p>
  <img src="https://img.shields.io/badge/STATA-Analysis-1f7a8c?style=for-the-badge" alt="STATA">
  <img src="https://img.shields.io/badge/SQL%20Server-Database-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server">
  <img src="https://img.shields.io/badge/Microsoft%20Excel-Data%20Cleaning-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel">
</p>

**Methods:**  
- **Descriptive statistics:** frequencies, medians, and interquartile ranges (IQR)  
- **Time-to-event analysis:** median time to TB diagnosis post-TPT  
- **Stratified tables** by HIV stage, adherence, and opportunistic infections (OIs)  
- Optional **Cox proportional hazard models** for sensitivity checks  

---

## 🖥️ Environment / Platforms
- **SQL Server** — dataset construction and variable derivation  
- **STATA** — statistical analysis and survival summaries  
- **EMR & Pharmacy linkage** — combined adherence and clinical records for risk profiling  

---

## 🧭 Step-by-Step Workflow
1. **Define cohort** — PLHIV completing TPT between 2014–2020  
2. **Extract and clean data** — remove duplicates, check treatment completion consistency  
3. **Compute post-TPT TB timing** — event calculation and censoring rules  
4. **Stratify** — by baseline WHO stage, ART/TPT adherence, and OIs  
5. **Summarize results** — descriptive tables, time-to-event histograms, and clinician briefs  

---

## 📦 Key Outputs / Deliverables
- **Descriptive summary tables** for TB post-TPT cases  
- **Time-to-event visualizations** (histograms, median survival plots)  
- **Risk profile briefs** for clinical decision support  

---

## 📈 Results & Impact
- **Cohort:** 25,225 PLHIV completed TPT  
- **TB after TPT:** 1.7% (n=423) developed TB post-completion  
- **Common characteristics:** advanced HIV stage (55%), poor ART/TPT adherence (57%), and frequent OIs (39%)  
- **Median time to TB:** 32.9 months (IQR: 18.3–48.2)  
- **Programmatic impact:** guided **targeted adherence support** during and after TPT, influencing follow-up policies  

---

## 🔧 Lessons Learned / Future Improvements
- Introduce **early-warning adherence indicators** within EMR.  
- Combine **viral load and symptom data** for automated follow-up triggers.  
- Expand analysis to evaluate **recurrent TB prediction models**.  

---

## 🖼️ Visuals & Documentation
- **Histograms** showing time-to-TB distribution  
- **Heatmaps** of clinical and adherence risk profiles  
- **Survival summary visuals** for program review presentations  

---

## 🏷️ Tags / Keywords
`#TPT` `#PLHIV` `#DescriptiveAnalysis` `#STATA` `#SQL` `#HIV` `#TB` `#TimeToEvent` `#ProgramEvaluation`

