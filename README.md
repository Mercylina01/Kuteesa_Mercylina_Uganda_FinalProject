# Kuteesa_Mercylina_Uganda_FinalProject
# Maternal Health Risk Classification  Rural Tanzania

## Project Overview

This project applies machine learning classification techniques** to clinical data collected from 8,817 pregnant women attending primary health facilities across five rural districts in Tanzania, with the goal of building a reliable model for early identification of high-risk pregnancies to support timely medical intervention and reduce maternal mortality.

## Dataset

**Source:** Mwifunyi, R. et al. (2025). Dataset for Maternal Health Risks Stratification (MHRS) in Tanzania (Version 1). Zenodo. [https://doi.org/10.5281/zenodo.15309733](https://doi.org/10.5281/zenodo.15309733)

**Collection:** May 2024 – March 2025, across five districts (Chamwino, Mkuranga, Meatu, Mbulu, Kilolo) spanning Central, Coastal, Lake, Northern, and Southern Highlands zones.

**Raw dataset:** 683 columns covering demographics, obstetric history, medical history, lifestyle, clinical measurements across up to 8 antenatal visits, delivery outcomes, postnatal follow-up.

**Target variable:** Risk— binary (high / low)

**Engineered features (36):** Demographics (age, height, weight, BMI), obstetric history (gravidity, parity, stillbirths, caesarean), medical conditions (hypertension, diabetes, HIV, sickle cell, etc.), lifestyle (smoking, alcohol, IPV), and Visit 1 clinical measurements (BP, pulse, temperature, haemoglobin).

## Methods

Six classification models trained and compared:

1. Logistic Regression
2. K-Nearest Neighbors
3. Decision Tree
4. Random Forest
5. Gradient Boosting
6. Support Vector Machine

Hyperparameter tuning via GridSearchCV with stratified 5-fold cross-validation.

**Top predictor:** Haemoglobin level at first antenatal visit , followed by BMI, gravidity, pulse rate, and blood pressure.





