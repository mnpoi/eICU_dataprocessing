# eICU Data Processing

## Project Overview

This project aims to process the eICU dataset, focusing on various medical conditions. The main goal of the project is to provide cleaned, preprocessed, and analyzed data for further machine learning and statistical analysis in medical research.

## Project Details

### AKI (Acute Kidney Injury)
- `patient.ipynb`: Filter patients with Acute Kidney Injury (AKI) for further analysis.

### AMI (Acute Myocardial Infarction)
- `patient.ipynb`: Filter patients with Acute Myocardial Infarction (AMI) for further analysis.
(ICD codes can be changed in the script to filter different conditions.)

### HF (Heart Failure)
- `lab_hf.ipynb`: Processes lab data, focusing on laboratory test results for HF patients.
- `patient.ipynb`: Filters patients with Heart Failure (HF).
- `vasopre.ipynb`: Processes vasopressor data for Heart Failure patients.
- `vital.ipynb`: Processes vital signs data for Heart Failure patients.

### preprocessing (Data Preprocessing)
These scripts are used for cleaning, feature engineering, and merging the eICU dataset:
- `apache.ipynb`: Processes Apache data.
- `diagnosis.ipynb`: Processes diagnosis-related data.
- `lab.ipynb`: Processes lab test data.
- `Merge.ipynb`: Merges data from various modules.
- `patient.ipynb`: Processes patient data.
- `treatment.ipynb`: Processes treatment-related data.
