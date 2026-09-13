# nhs-asthma-prescribing-analysis
Python analysis of NHS primary care asthma inhaler prescribing, cost and geographic variation in 2025/26

# NHS Asthma Prescribing Analysis

A Python data analysis project exploring prescribing volume, NHS expenditure, geographic variation and monthly trends across six selected asthma inhaler brands in NHS primary care during the 2025/26 financial year.

## Project Overview

This project uses publicly available NHS primary care prescribing data to investigate differences in prescribing patterns and expenditure across six selected asthma inhaler brands.

The analysis includes Ventolin, Clenil Modulite, Pulmicort, Symbicort, Fostair and Seretide. These represent a range of therapeutic classes including SABA, ICS and ICS/LABA treatments.

## Research Question

**How do prescribing volume, cost and geographic variation differ between selected commonly prescribed asthma inhaler brands in NHS primary care during the 2025/26 financial year?**

The analysis addresses four questions

1. Which inhaler brands had the highest prescribing volume and total actual cost?
2. How does cost per prescription item differ between the selected inhaler brands?
3. How much does prescribing vary between NHS areas for each inhaler brand?
4. How did prescribing volume and cost change over time from April 2025 to March 2026?

## Data

Data were obtained from OpenPrescribing, developed by the Bennett Institute for Applied Data Science at the University of Oxford using NHS primary care prescribing data.

The analysis covers April 2025 to March 2026.

Prescription items measure prescribing activity and do not represent the number of individual inhalers supplied or the number of patients treated.

## Tools and Skills

Python  
pandas  
Matplotlib  
Jupyter Notebook  
Data cleaning and preparation  
Data aggregation  
Data visualisation  
Exploratory data analysis  
Healthcare data interpretation

## Key Findings

Fostair had the highest prescribing volume with approximately 4.19 million prescription items and the highest total actual cost at approximately £150.35 million.

Fostair and Symbicort had the highest average actual cost per prescription item** at approximately £35.86 and £35.21 respectively.

Total expenditure was influenced by both prescribing volume and cost per item. Seretide had fewer prescription items than Ventolin but substantially greater total expenditure.

Prescribing volume varied considerably between NHS areas. Pulmicort showed the greatest relative geographic variation among the selected brands.

Monthly prescribing fluctuated throughout the financial year rather than following a consistent trend across all brands. Symbicort showed a general increase towards the end of the study period.

## Limitations

Geographic comparisons use absolute prescription item totals and are not adjusted for population or practice list size. Differences between NHS areas may therefore partly reflect differences in the populations they serve.

The selected inhalers represent different medicines, formulations and therapeutic classes. Differences in prescribing and cost should therefore not be interpreted as direct comparisons between interchangeable treatments.

Only one financial year was analysed which limits the ability to identify longer term or seasonal trends.

The project examines six selected inhaler brands rather than all medicines used in asthma management.

