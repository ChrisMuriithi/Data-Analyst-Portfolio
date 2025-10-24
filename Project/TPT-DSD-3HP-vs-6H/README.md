# TPT Outcomes in DSD Models: 3HP vs 6H in PLHIV (2020–2022)

> Comparative analysis of **TB Preventive Therapy (TPT)** completion and **loss-to-follow-up (LTFU)** among PLHIV, evaluating short-course **3HP** (weekly rifapentine/isoniazid) versus long-course **6H** (isoniazid) regimens under **Differentiated Service Delivery (DSD)** and **Standard of Care (SOC)** models.

---

## 👤 Role & Problem Statement
**Role:** *Data Analyst* — led **SQL cohort assembly**, **STATA modeling**, and **dashboard development**.  
**Problem solved:** Provided quantitative evidence that **short-course TPT (3HP)** under **DSD** significantly improves treatment completion compared to traditional 6H or SOC models.

---

## 🧰 Languages, Utilities & Statistical Methods

<p>
  <img src="https://img.shields.io/badge/STATA-Analysis-1f7a8c?style=for-the-badge" alt="STATA">
  <img src="https://img.shields.io/badge/SQL%20Server-Database-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboards-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
</p>

**Methods:**  
- **Logistic regression** for treatment completion and LTFU  
- **Subgroup analyses** by regimen (3HP vs 6H) and delivery model (DSD vs SOC)  
- **Interaction terms** to assess combined regimen–model effects  

---

## 🖥️ Environment / Platforms
- **SQL Server** — cohort design and episode construction  
- **STATA** — regression modeling and hypothesis testing  
- **Power BI** — visualization and KPI tracking  
- **Ecare EMR** — regimen and model tagging via digital flags  

---

## 🧭 Step-by-Step Workflow
1. **Indicator mapping** → define completion, LTFU, and regimen codes  
2. **Regimen classification** → 3HP (weekly) vs 6H (daily)  
3. **Data cleaning** → remove duplicates, define episode windows  
4. **Modeling** → logistic regressions, subgroup & interaction analyses  
5. **Dissemination** → summary tables, Power BI visual briefs, and policy presentation  

---

## 📦 Key Outputs / Deliverables
- Odds ratio tables for **completion** and **LTFU**  
- **Interaction plots** showing regimen × model outcomes  
- Completion **KPI trackers** and Power BI dashboards  

---

## 📈 Results & Impact
- **3HP regimen:** 92.6% completion; DSD significantly better than SOC  
  - **OR 6.9 [5.1–9.2]**, **LTFU OR 0.06 [0.02–0.20]**  
- **6H regimen:** No statistically significant difference between DSD and SOC  
- **Recommendation:** Prioritize **3HP under DSD** for improved adherence and efficiency in PLHIV programs.  

---

## 🔧 Lessons Learned / Future Improvements
- Incorporate **stock availability** and **adverse event (AE)** monitoring to contextualize outcomes.  
- Conduct **cost-effectiveness** evaluations for regimen-model combinations.  
- Explore **survival analysis** for time-to-completion modeling.  

---

## 🖼️ Visuals & Documentation
- **Forest plots** by regimen and service model  
- **Completion KPI cards** highlighting 3HP vs 6H performance  
- **Sankey diagram** visualizing LTFU flows between models  

---

## 🏷️ Tags / Keywords
`#TPT` `#3HP` `#6H` `#STATA` `#SQL` `#LogisticRegression` `#PLHIV` `#DSD` `#TBPrevention`

