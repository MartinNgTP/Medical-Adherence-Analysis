# 💊 Medication Adherence Analysis

## 📊 Project Overview
This project analyzes **medication adherence** among heart disease patients, using data from a health insurance company. The analysis focuses on adherence patterns for **ACE inhibitors, beta blockers, and statins**, identifying key factors that influence medication adherence rates.

## 📦 Dataset
- **Source:** Health insurance company dataset
- **Files:**
  - `data/baseline_measurements.csv`
  - `data/adherence.csv`
- **Features:**
  - `patient_id`: Unique patient identifier
  - `days_since_diagnosis`: Days elapsed since initial diagnosis
  - `ace_inhibitor`, `beta_blocker`, `statin`: Medication adherence records (binary values: 1 for filled, 0 for not filled)
  - `age`, `gender`, `region`, `diabetes`, `baseline_condition`: Patient demographics and health history

## 🚀 Analyses Performed
- **Medication Adherence Report**
  - 📈 Follow-up duration and adherence rates
  - 💊 Prescription initiation timelines
  - 🔬 Impact of demographic and clinical factors on adherence
  - 📊 Linear regression modeling for adherence predictors
  
- **Independent Investigation**
  - 📌 Trends in multi-medication adherence
  - 📊 Logistic regression on early medication initiation
  - 📉 Impact of prescription timing on long-term adherence

## ⚙️ Evaluation Metrics
The adherence models are evaluated based on:
- **One-Year Adherence Rate:** Percentage of days medication was possessed in the first year post-diagnosis.
- **Prescription Initiation Rate:** Proportion of patients who filled a prescription within the first two weeks.
- **Regression Analysis:** Understanding how age, gender, region, and pre-existing conditions affect adherence.

## 📈 Results
- Detailed findings are documented in the `reports/` folder.
- Regression models highlight key factors influencing adherence.
- Comparisons between early vs. late prescription initiators provide actionable insights.

## 🌍 Reports
Check out the reports [here](https://martinngtp.github.io/Medical-Adherence-Analysis/).

## 📚 Acknowledgments
- Health insurance company for data provisioning
- Libraries: `data.table`, `ggplot2`, `rmarkdown`, `dplyr`, `glm`, `MASS`

---

Made by Martin Ng

