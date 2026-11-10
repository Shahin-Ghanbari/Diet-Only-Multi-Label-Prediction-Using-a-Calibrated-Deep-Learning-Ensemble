# Diet-Only Multi-Label Prediction Using a Calibrated Deep Learning Ensemble

A research notebook that investigates whether 24-hour dietary recalls can support multi-label prediction for hypertension, diabetes, and thyroid dysfunction.

[Open the research notebook](Final_Code.ipynb) · [Explore the NHANES data source](https://www.cdc.gov/nchs/nhanes/about/index.html)

## Research workflow

1. Use dietary features from the National Health and Nutrition Examination Survey (NHANES).
2. Train neural network models and combine their outputs through per-label stacking.
3. Calibrate probabilities for each condition.
4. Evaluate decision thresholds using precision, recall, and the number of alerts per 1,000 people screened.
5. Examine model predictions using SHAP.

## Data and reproduction

The repository contains [`Final_Code.ipynb`](Final_Code.ipynb). The NHANES datasets are available from the CDC and must be obtained separately. Review the notebook's data-loading cells for the expected inputs and local paths before running it.

## Paper

**Diet-Only Multi-Label Prediction of Hypertension, Diabetes, and Thyroid Dysfunction Using a Calibrated Deep Learning Ensemble**

Shahin Ghanbari, Elaheh Homayounvala, and Sahar Al-Sudani
