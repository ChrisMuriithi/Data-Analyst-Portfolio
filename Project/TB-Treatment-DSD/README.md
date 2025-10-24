# TB Treatment DSD Models: Outcomes vs Standard of Care (2020–2022)

> A comparative analysis assessing the effectiveness of **Differentiated Service Delivery (DSD)** models versus **Standard of Care (SOC)** in managing drug-sensitive TB during COVID-19 disruptions across Nairobi’s informal settlements.

---

## 👤 Role & Problem Statement
**Role:** *Data Analyst* — designed analysis plan, developed reproducible SQL/STATA pipelines, and conducted comparative outcome analysis.  
**Problem solved:** Determined which care model (**DSD** vs **SOC**) yielded better **treatment success** and **mortality** outcomes under service delivery constraints.

---

## 🧰 Languages, Utilities & Statistical Methods

<p>
  <img src="https://img.shields.io/badge/STATA-Analysis-1f7a8c?style=for-the-badge" alt="STATA">
  <img src="https://img.shields.io/badge/SQL%20Server-Database-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboards-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Excel-Data%20Cleaning-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel">
</p>

**Methods:**  
- Logistic regression (crude & adjusted **odds ratios**)  
- **Risk difference** estimation and sensitivity analysis  
- **Subgroup analysis** by disease severity  

---

## 🖥️ Environment / Platforms
- **SQL Server** — case registry and data extraction  
- **STATA** — statistical modeling and results validation  
- **Power BI Service** — DSD dashboard and visualization  
- **Ecare EMR customization** — added DSD enrollment and follow-up modality flags  

---

## 🧭 Step-by-Step Workflow
1. **Problem mapping** → identification of indicators (Treatment Success, Death, LTFU)  
2. **SQL extracts** → automated dataset generation from EMR  
3. **Modeling in STATA** → logistic regressions and sensitivity checks  
4. **Visualization** → Power BI dashboards for site-level monitoring  
5. **Dissemination** → summarized tables and insights for policy briefs  

---

## 📦 Key Outputs / Deliverables
- Odds ratio tables (crude & adjusted)  
- Site performance league tables  
- Reproducible SQL/STATA scripts  
- Interactive **Power BI DSD Monitoring Dashboard**

---

## 📈 Results & Impact
- **Sample size:** DSD (n=1,049) vs SOC (n=1,473)  
- **Treatment success:** 83.5% (DSD) vs 76.0% (SOC) → **OR 1.6 [1.3–2.0]**  
- **Mortality:** 3.1% (DSD) vs 6.5% (SOC) → **OR 0.5 [0.3–0.7]**  
- **Policy impact:** Evidence informed the **scale-up of DSD models**, optimizing clinic workload and maintaining treatment outcomes.

---

## 🔧 Lessons Learned / Future Improvements
- Use **Inverse Probability of Treatment Weighting (IPTW)** or **Propensity Score Matching (PSM)** to adjust for disease severity bias.  
- Collect **socioeconomic covariates** for more granular insights.  
- Expand analysis to include **SMS adherence nudges** and digital engagement metrics.

---

## 🖼️ Visuals & Documentation
- Outcome **funnel plots** by site  
- Temporal **run charts** of DSD outcomes  
- **Heatmap** visualizing DSD uptake by sub-county  

---

## 🏷️ Tags / Keywords
`#DataAnalysis` `#STATA` `#SQL` `#TB` `#DSD` `#LogisticRegression` `#ProgramOutcomes`

