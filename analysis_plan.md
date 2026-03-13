---
title: "Statistical Analysis Plan"
author: "Richard Adejumola"
date: "2026-03-09"
output: 
  html_document:
    toc: true
    number_sections: true
    code_folding: show
---

# Background 

Diabetes is a metabolic disease that affects the body’s ability to metabolize glucose [1]. Without early diagnosis or proper clinical management, diabetes can affect domains of health, including physical and mental health [2]. With regard to mental health, diabetes has been associated with depression in a bidirectional relationship---either as the outcome results in a statistically significant effect size [3]. In addition to the association between diabetes and depression, the literature suggests that the depression rates are three times higher among persons with type 1 diabetes compared to the healthy population, as well as two times higher in people with type 2 diabetes [4]. 



# Research Objectives 

Using machine learning classification algorithms: 

1. Estimate the associations between lifetime diagnosis of depression and diabetes diagnosisadjusting for sociodemographic characteristics, comorbidities, and health habits (e.g., smoking & alcohol use) for adults living in the United States

2. Estimate the associations between lifetime diagnosis of depression and type of diabetes, adjusting for the aforementioned covariates among adults living with diabetes in the United States. 

3. Evaluate and compare the performances of the algorithm for Objectives 1 & 2. 

# Methodology

## Study Design

The data used in this study will be obtained from the Behavioral Risk Factor Surveillance System (BRFSS) 2024 component [5]. The BRFSS is an annual telephone cross-sectional survey by the Centers for Disease Control and Prevention (CDC) to collect cross-sectional data on health-related indicators [5]. Eligible participants are aged 18 years and older with stable housing arrangements (i.e., living in a private household or college dorm), and randomly selected from participating states and territories in the US [5].  

## Outcome variable

* Lifetime diagnosis with depression 

## Independent variables & covariates

* Sociodemographics (state of residence, sex, BMI, marital status, education, employment, annual income)

* Health insurance

* Self-rated rating of physical health

* Comorbidities (heart attack, coronary heart disease, stroke, COPD, asthma, cancer, chronic kidney disease, arthritis)

* Health habits (last health checkup, exercise, smoking status)

* Diabetes (diagnosis, age at DM diagnosis, had a recent eye exam, took a DM education class, feet sore, last HbA1c check, insulin use)

## Algorithms

The machine learning techniques to be applied broadly include:

* Binary logistic regression
* Classification tree
* Principal component analysis 

# References

1. Alam U, Asghar O, Azmi S, Malik RA. General aspects of diabetes mellitus. Handbook of clinical neurology. 2014 Jan 1;126:211-22.
2. Robinson DJ, Coons M, Haensel H, Vallis M, Yale JF, Diabetes Canada Clinical Practice Guidelines Expert Committee. Diabetes and mental health. Canadian journal of diabetes. 2018 Apr 1;42:S130-41.
3. Holt RI, De Groot M, Golden SH. Diabetes and depression. Current diabetes reports. 2014 Jun;14(6):491.
4. Roy T, Lloyd CE. Epidemiology of depression and diabetes: a systematic review. J Affect Disord. 2012;142 Suppl:S8-S21. doi:10.1016/S0165-0327(12)70004-6 
5. CDC - 2024 BRFSS Survey Data and documentation [Internet]. Available from: https://www.cdc.gov/brfss/annual_data/annual_2024.html
