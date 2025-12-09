# MIMIC III Business Intelligence Healthcare Outcomes Analysis
A full-stack clinical data science project integrating EHR data modeling, feature engineering, clinical risk analysis, and interactive BI dashboards.

This project demonstrates how **real-world critical care data (MIMIC-III)** can be transformed into actionable insights through a complete pipeline:
Data extraction → Cleaning → Cohort Building → Feature Engineering → Outcome Modeling → BI visualization.

## Project Overview

This study analyzes **10,000 ICU patients** from the MIMIC-III database (de-identified EHR data from Beth Israel Deaconess Medical Center).
The end-to-end workflow includes:

✔ **Notebook 1**: Data ingestion & cohort building
✔ **Notebook 2**: Feature engineering & clinical variable extraction
✔ **Notebook 3**: Outcome modeling, mortality trends, lab trajectory analysis
✔ **Notebook 4**: Power BI star-schema + Dashboard design
✔ **Power BI Dashboard**: Interactive insights for clinicians & researchers

The project showcases:

1. Clinical data engineering
2. EHR preprocessing (ICU stays, labs, diagnoses)
3. Time-series lab feature extraction
4. Risk and outcome analytics
5. Dimensional modeling (FACT/DIM tables)
6. Power BI healthcare dashboard development

Tech Stack
| Layer                    | Tools / Technologies                 |
| ------------------------ | ------------------------------------ |
| **Data Source**          | MIMIC-III v1.4 (10,000 patients)     |
| **ETL & Cleaning**       | Python, Pandas, SQL                  |
| **Feature Engineering**  | NumPy, Pandas, Clinical Calculations |
| **Analytics & Modeling** | Python (Jupyter)                     |
| **BI Layer**             | Power BI Desktop                     |
| **Visualization**        | DAX, Power BI                        |
| **Data Modeling**        | Star Schema + Bridge Tables          |

## Key Features
**1. Demographic & Admission Analytics**
Age group distribution
Gender stratification
Insurance patterns
ICU admission types & LOS

**2. Lab-Based Clinical Risk Indicators**
Extracted labs include:
Creatinine
Lactate
Hemoglobin
Platelets
BUN

**3. ICD-9–Based Disease Burden Analysis**
Diagnosis mapping
Disease frequency
Comorbidity patterns

**4. Mortality & Outcome Prediction Signals**
30-day mortality
ICU vs hospital mortality
LOS patterns by diagnosis
High-risk biomarker patterns (elevated lactate, AKI risk, anemia)

**5. Interactive Power BI Dashboard**
Diagnosis-level filtering (bridge table solution)
Mortality KPIs
Admission Timelines

## Dashboard Preview
![Healthcare Data Analysis Dashboard](https://github.com/user-attachments/assets/608b0d4f-89da-4daf-ab2f-a5596e6222ac)

## Why This Project Matters

This project reflects the growing need for:
1. Data-driven hospital decision support
2. Outcome monitoring
3. Clinical risk stratification
4. Real-world EHR analytics
5. Scalable BI solutions in healthcare

It demonstrates how **modern analytics tools** can translate messy ICU data into **meaningful insights for clinicians and researchers**.

## Contributions

Feel free to submit pull requests or suggest enhancements!

