# 2023 Children's Health Survey Data Analysis

## Overview
This project analyzes survey data to explore the association between pediatric type 2 diabetes and socioeconomic factors, along with other relevant covariates. The analysis, performed in R, includes descriptive statistics, regression modeling, and summary table generation.

## Data
The dataset is not included in this repository due to size restrictions. 

The expected structure includes:

- **Diabetes status:** DIABETES, DIABETES_CURR  
- **Socioeconomic indicators:** FOODSIT, FPL_I1–FPL_I6, ACE1  
- **Covariates:** SC_AGE_YEARS, SC_SEX, SC_RACE_R, PHYSACTIV

## Reproducibility
To reproduce the analysis:
1. Place the dataset in a local `data/` folder
2. Update the file path in `data_cleaning.Rmd`
3. Run the script

## Tools Used

- **Language:** R  
- **Data import / cleaning:** rio, haven, janitor, labelled  
- **Data manipulation / analysis:** tidyverse, rms, Hmisc, broom, marginaleffects, modelsummary, lmtest, pROC  
- **Reporting / tables:** knitr, kableExtra, flextable, gtsummary  
- **Project organization:** here, broom.helpers

## Author
**Timothy Corkery** – [GitHub](https://github.com/Tcork5)
