# Maternal Mortality Racial Disparities (CDC WONDER, 2018–2024)

*An epidemiologic analysis of racial disparities in U.S. maternal mortality using CDC WONDER data (2018–2024).*

## Overview

This project presents an epidemiologic analysis of age-adjusted maternal mortality rates in the United States from 2018 through 2024. The analysis focuses on racial disparities between Black and White populations.

Maternal mortality is a critical indicator of population-level health equity and health system performance.

The figure below displays the temporal trend in the age-adjusted Black–White maternal mortality ratio (CDC WONDER, 2018–2024). Ratios above 1 indicate disproportionate risk among Black women relative to White women.

![Maternal Mortality Ratio](ratio.png)
---
## Public Health Significance

Maternal mortality is widely used as a sentinel indicator of healthcare system performance, access to care, and structural inequities. Persistent racial disparities in maternal outcomes reflect complex interactions between social determinants of health, healthcare quality, and systemic inequity.

Understanding both absolute and relative disparities is essential for accurate interpretation of trends.

---

## Research Objectives

- Evaluate temporal trends in maternal mortality  
- Quantify absolute disparity (rate difference)  
- Quantify relative disparity (rate ratio)  
- Assess whether trends differ by race using linear regression with interaction  

---

## Data Source

- CDC WONDER Multiple Cause of Death database  
- ICD-10 codes O00–O99 (pregnancy, childbirth, and the puerperium)  
- Age-adjusted mortality rate per 100,000 population  

Raw CDC data files are not included in this repository due to size and licensing constraints.

---

## Methods

A retrospective descriptive analysis was conducted using annual national mortality data. Disparities were evaluated using both absolute and relative measures.

Temporal trends were assessed using ordinary least squares (OLS) regression, including a Year × Race interaction term to evaluate differences in trend slopes.

Findings are descriptive and should not be interpreted as causal.

---

## Key Findings

- Maternal mortality increased sharply in 2021 during the COVID-19 pandemic.
- Rates declined in 2022–2024; however, the Black–White disparity ratio increased in 2023.
- The increase in relative disparity in 2023 appears to be driven by sharper post-pandemic declines in mortality among White mothers rather than a proportional worsening among Black mothers.
- Across the study period, Black maternal mortality was consistently approximately three times higher than White maternal mortality.

---

## Repository Contents

- `maternal_mortality_racial_disparities_2028_2024.ipynb`  
  Complete analysis notebook with visualizations and regression modeling.

---

  ## Technical Stack

- Python (pandas, numpy, statsmodels, matplotlib)
- Ordinary Least Squares regression
- CDC WONDER data extraction
- Jupyter Notebook

## Limitations
- CDC WONDER data are aggregated and do not allow individual-level risk adjustment.

- Potential reporting delays or classification changes may affect recent years.

- Race categories are restricted to available reporting classifications.
