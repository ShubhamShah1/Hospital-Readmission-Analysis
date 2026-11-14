# Hospital-Readmission-Analysis
Data Analytics Case Study on Hospital Readmission Analysis to Identify Risk Factors, Improve Patient Care, and Reduce Readmissions.
Hospital Readmission Analysis
Project: Reducing Readmissions: A Data Analytics Case Study for
Improved Patient Care
Author: Shubham Shah
Project Overview
This project focuses on analyzing hospital admission data to identify
patterns and factors associated with patient readmissions. The goal is
to support better patient care, improve hospital resource allocation,
and help identify opportunities to reduce avoidable readmissions.

The case study is framed around a hospital administration scenario and
uses the Hospital Administration dataset published on Kaggle.
Problem Statement
The hospital has experienced an increase in readmission rates. This can
increase healthcare costs and may indicate opportunities to improve the
quality and continuity of patient care.

The analysis is intended to explore demographic, clinical, medication,
and healthcare-utilization factors associated with readmission.
Dataset
- Dataset: Hospital Administration Data
- Source: Kaggle -- Hospital Administration
  Data
- Workbook included: Hospital Administration Analysis.xlsx
The dataset description includes encounter and patient identifiers,
demographic details, length of stay, medical specialty, procedures,
medications, prior outpatient/emergency/inpatient visits, diagnosis
codes, and readmission status.
Important fields
  Field                     Description
  encounter_id            Unique identifier of an encounter
patient_id              Unique identifier of a patient
race, gender, age   Patient demographic information
time_in_hospital        Length of hospital stay in days
medical_specialty       Specialty of the admitting physician
num_lab_procedures      Number of lab tests performed
num_procedures          Number of non-lab procedures performed
num_medications         Number of distinct medications prescribed
number_outpatient       Outpatient visits in the preceding year
number_emergency        Emergency visits in the preceding year
number_inpatient        Inpatient visits in the preceding year
number_diagnoses        Number of diagnoses recorded
change                  Whether diabetic medication was changed
diabetesMed             Whether diabetic medication was prescribed
readmitted              Readmission indicator as defined in the case study

The weight field contains many missing values. Medication fields X1
to X25 are indicators whose specific medication names are not provided
in the supplied data dictionary.
Analysis Questions
Basic Level
1. Readmission rates across age groups.
2. Average length of stay by medical specialty.
3. Relationship between prior emergency visits and readmission.
4. Readmission proportion among patients with diabetes.
5. Readmission rates by diabetic medication change.
6. Relationship between lab procedures and readmission.
7. Readmission rates by race and gender.
8. Weight completeness, weight categories, and readmission.
9. Relationship between medication count and length of stay.
10. Prior outpatient visits and readmission.
Medium Level
1. Readmission trends over time, if suitable date fields are available.
2. Comorbidities, length of stay, and readmission.
3. Discharge disposition and readmission, if disposition data is
   available.
4. Demographics and interventions received.
5. Prior healthcare visits by primary diagnosis.
6. Longer-term patient outcomes, if supported by additional data.
7. Medication indicator patterns across specialties.
8. Weight categories, diagnosis codes, and readmission.
9. Diabetic medication indicators and readmission.
10. Patient satisfaction and readmission, if satisfaction data is
    available.
Advanced Level
1. Predictive model for readmission risk.
2. Patient segmentation using healthcare utilization and outcomes.
3. Financial impact of readmissions, if cost data is available.
4. Social determinants of health and readmission, potentially using
   external data.
5. Post-discharge follow-up program recommendations based on findings.
Stakeholders
Internal: Hospital board/trustees, C-suite executives, department
heads, physicians, nurses, allied health professionals, and
administrative staff.

External: Patients, families and caregivers, insurance
companies/payers, government agencies, suppliers, and the community.
Repository Contents
- Hospital Administration Analysis.xlsx --- workbook supplied for
  the project.
- README.md --- project overview, dataset information, and analysis
  scope.
If you add a separate case study document, solution guide, dashboard,
presentation, or cleaned dataset, include those files in the repository
and update this list so it accurately reflects the final contents.
Notes and Limitations
- The case study questions describe analyses to perform; this README
  does not claim that every question has already been answered.
- Some questions depend on fields that may not be present in the
  supplied workbook, such as admission/discharge dates, discharge
  disposition, patient satisfaction, and cost data. Check the actual
  columns before attempting those analyses.
- The data dictionary describes readmitted as a binary indicator
  (1 for readmitted within 30 days and 0 otherwise). Confirm this
  coding against the actual workbook before calculating results.
- The dataset contains patient-related information. Do not publish
  identifiable or sensitive patient records. Use de-identified,
  appropriately licensed data and follow applicable privacy
  requirements.
How to Use
1. Download or clone this repository.
2. Open Hospital Administration Analysis.xlsx in Microsoft Excel or a
   compatible spreadsheet application.
3. Review the dataset columns and data dictionary.
4. Perform the analyses that are supported by the available fields.
5. Document methods, assumptions, limitations, and findings before
   presenting conclusions.
Author
Shubham Shah
