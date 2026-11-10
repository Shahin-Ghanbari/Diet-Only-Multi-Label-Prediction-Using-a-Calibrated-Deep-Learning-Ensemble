# Diet-Only Multi-Label Prediction Using a Calibrated Deep Learning Ensemble

A research notebook exploring whether 24-hour dietary recalls can support prediction of multiple health outcomes.

| | |
| --- | --- |
| **Research question** | How well can dietary information alone support prediction of hypertension, diabetes and thyroid dysfunction? |
| **Data** | Dietary recall data from the US National Health and Nutrition Examination Survey (NHANES). |
| **Method** | Train neural networks, combine their predictions through per-outcome stacking and calibrate probabilities. Compare thresholds using precision, recall and alerts per 1,000 people screened, and explore model explanations with SHAP. |

## Notebook and data

[Open the research notebook](Final_Code.ipynb). Obtain the NHANES datasets separately from the CDC and review the notebook's data-loading cells for the expected inputs and local paths. [NHANES data source](https://www.cdc.gov/nchs/nhanes/about/index.html)

## Paper

*Diet-Only Multi-Label Prediction of Hypertension, Diabetes, and Thyroid Dysfunction Using a Calibrated Deep Learning Ensemble*

Shahin Ghanbari, Elaheh Homayounvala, and Sahar Al-Sudani

[Back to the research portfolio](https://github.com/Shahin-Ghanbari#featured-research)
