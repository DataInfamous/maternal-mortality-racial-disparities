# Maternal Mortality Racial Disparities (CDC WONDER, 2018–2024)

## Overview

This project presents an epidemiologic analysis of age-adjusted maternal mortality rates in the United States from 2018 through 2024. The analysis focuses on racial disparities between Black and White populations.

Maternal mortality is a critical indicator of population-level health equity and health system performance.

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

Analyses are descriptive and do not establish causality.

---

## Key Findings

- Maternal mortality increased sharply in 2021 during the COVID-19 pandemic.
- Rates declined in 2022–2024; however, the Black–White disparity ratio increased in 2023.
- The increase in relative disparity was driven by faster declines among White mothers rather than worsening outcomes among Black mothers.
- Across the study period, Black maternal mortality remained substantially higher than White maternal mortality.

---

## Repository Contents

- `maternal_mortality_racial_disparities_2028_2024.ipynb`  
  Complete analysis notebook with visualizations and regression modeling.
