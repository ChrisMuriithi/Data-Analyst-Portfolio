# Secondary TB Prevention in PLHIV: Impact of Post-TB IPT (2012–2021)

> A retrospective cohort across **14 clinics** in Nairobi informal settlements evaluating whether **isoniazid preventive therapy (IPT)** after TB treatment reduces **TB recurrence** among **PLHIV on ART**.

---

## 👤 Role & Problem Statement
**Role:** *Data Analyst & MEL Lead* — assembled the analysis dataset, executed survival analyses, and produced figures/tables for abstract/manuscript.  
**Problem solved:** Quantified real-world effectiveness of **post-TB IPT** on TB recurrence to inform scale-up decisions.

---

## 🧰 Languages, Utilities & Statistical Methods

<p>
  <img src="https://img.shields.io/badge/STATA-Analysis-1f7a8c?style=for-the-badge" alt="STATA">
  <img src="https://img.shields.io/badge/SQL%20Server-Database-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server">
  <img src="https://img.shields.io/badge/Excel%20%2F%20Power%20Query-Data%20Prep-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel Power Query">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboards-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
</p>

**Methods:**  
- Extended **Cox proportional hazards** with time-varying covariates (VL suppression)  
- **Incidence rates** per 1,000 person-years  
- **Kaplan–Meier** TB-free survival curves  
- **Adjusted hazard ratios (aHR)** with 95% CIs

---

## 🖥️ Environment / Platforms
- On-prem **SQL Server** for cohort assembly; **STATA 15/17** for analysis; **Power BI Service** for QC & trends  
- Data sources: **Ecare EMR exports** + program registers; deterministic/probabilistic linkage via **UPI / ART number**

---

## 🧭 Step-by-Step Walkthrough
1. **Problem ID & indicator mapping** → TB episodes, IPT completion, VL status  
2. **Data design** → SQL cohort builder; de-duplication & episode sequencing  
3. **Cleaning & validation** → missingness checks, date logic, person-time accrual  
4. **Analysis & visualization** → Cox models; KM curves; subgroup by sex/VL  
5. **Dissemination** → abstract, survival plot, policy brief  

**Evaluation frames:** Process (data quality) · Outcome (TB recurrence) · System (continuity of care)

---

## 📦 Key Outputs / Deliverables
- De-identified **analysis dataset**, **STATA `.do`** files, survival plots, aHR tables  
- **Data dictionary** & cohort-build **SQL scripts**  
- **Power BI QC dashboard** for monthly recurrence signals

---

## 📈 Results & Impact
- **TB recurrence:** **14.9/1000-PY** (post-TB IPT) vs **42.5/1000-PY** (no IPT)  
- **Median time to TB:** **6.0 years** (IPT) vs **2.0 years** (no IPT)  
- **aHR 0.12 (95% CI 0.06–0.23)** → **88% lower hazard** with IPT  
- **Program impact:** Evidence adopted to support **post-TB IPT scale-up**

---

## 🔧 Lessons Learned / Future Improvements
- Add **propensity score weighting/IPTW** to mitigate selection bias  
- Operationalize **automated survival dashboards** (scheduled refresh)  
- Integrate **IPT eligibility & stock logic** into EMR alerts for timely initiation

---

## 🖼️ Visuals & Documentation (optional)
- Kaplan–Meier survival figure  
- Forest plot of adjusted hazard ratios  
- Cohort flow diagram

---

## 🏷️ Tags / Keywords
`#DataAnalysis` `#STATA` `#SQL` `#CoxPH` `#HIV` `#TB` `#IPT` `#ProgramEvaluation`
