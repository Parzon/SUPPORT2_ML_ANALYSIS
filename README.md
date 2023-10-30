# SUPPORT2_ML_ANALYSIS
Dataset Overview: SUPPORT2

Background:
The SUPPORT2 dataset includes data on 9,105 critically ill patients from five U.S. medical centers between 1989-1994. The data focuses on nine specific disease categories and aims to ascertain 2- and 6-month survival rates using patient details related to physiology, demographics, and disease severity. It's part of a larger effort to improve end-of-life decision-making for patients.

Dataset Details:

Dataset Characteristics: Tabular, Multivariate
Subject Area: Life Science
Tasks: Classification, Regression, and Other
Feature Type: Real, Categorical, Integer
Instances: 9,105
Features: 42
Objective:
The dataset was created to design and test a model that predicts survival over 180 days for seriously ill hospitalized adults. It also compares these predictions to existing systems and physicians' estimates. The ultimate goal is to aid decision-making for patients nearing end-of-life, ensuring they retain control and dignity.

Funding: Robert Wood Johnson Foundation

Dataset Composition:
Each instance represents critically ill patients admitted to U.S. hospitals with advanced illness stages. While there are no predefined data splits, a standard train-test split is recommended. Notably, the dataset contains sensitive information, including race, gender, income, and education level.

Imputation Advice:
Missing values for specific baseline physiologic data can be imputed using the provided fill-in values.

Data Sources:
Information is sourced from medical records, personal interviews, and the National Death Index (NDI). The dataset captures various details, including clinical, treatment, and decision-making patterns.

Usage Context:
This dataset can be employed for tasks like binary classification (hospital death), ordinal regression (functional disability assessment), and regression (predicting hospital costs and length of stay).

Citation:
Harrel,Frank. (2023). SUPPORT2. UCI Machine Learning Repository. https://doi.org/10.3886/ICPSR02957.v2

Acknowledgements:
If utilizing this dataset, acknowledge Vanderbilt University Department of Biostatistics, Professor Frank Harrell 2022. https://hbiostat.org/data/

Keywords: algorithmic fairness, clinical medicine

Creator:
Frank Harrel, Department of Biostatistics. Email

License: Check the linked dataset for licensing details.
