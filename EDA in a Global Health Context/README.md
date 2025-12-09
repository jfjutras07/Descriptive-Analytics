# Descriptive Analytics Project: Global Health Data Cleaning and Harmonization

This project analyzes **multi-clinic and hospital health datasets** to extract **descriptive insights and ensure data consistency across sources**. The aim is to provide a **clean, harmonized, and validated dataset** that supports **clinical analysis, anomaly detection, and downstream research**.

## Contents

1. **eda-in-a-global-health-context-part-1.ipynb** – Introduction and Initial Data Cleaning  
   - Load the five CSV datasets from all clinics and hospitals  
   - Perform an initial overview to inspect data structure, missing values, and inconsistencies  
   - Standardize and rename columns to ensure consistent naming across all sources  
   - Clean and harmonize administrative columns (e.g., patient IDs, visit dates) without modifying medical or numerical values  

2. **part-2-data-cleaning.ipynb** – Patient and Hospital Data Standardization  
   - Standardize and clean patient-related columns (IDs, names, visit numbers, demographics) to ensure consistency  
   - Clean hospital-related columns (hospitalization status, days, tests, and imaging requirements) while preserving medical and numerical values  
   - Merge all sources into a single dataset for further analysis  
   - Convert columns to appropriate data types (numerical, categorical, datetime) for analysis  

3. **part-3-duplicate-and-clinical-data-handling.ipynb** – Duplicate Visits and Clinical Data Review  
   - Identify and handle duplicate visits, including detection of patient transfers across clinics  
   - Review and correct missing or inconsistent clinical and diagnostic data  
   - Perform initial imputation of vital signs for stable patients  
   - Improve dataset integrity by addressing logical inconsistencies and recording errors  

4. **part-4-data-validation-and-derived-metrics.ipynb** – Final Cleaning, Derived Columns, and Data Validation  
   - Identify and correct abnormal clinical values (implausible blood pressure readings, height discrepancies, age mismatches)  
   - Reorganize and standardize dataset structure for easier validation and analysis  
   - Create derived columns (BMI and age category) to support clinical rules and detect anomalies  
   - Apply data quality and clinical validation rules, flag inconsistencies, and correct them where appropriate  

