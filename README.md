# Diet-Only Multi-Label Prediction Using a Calibrated Deep Learning Ensemble

This repository contains the code for a diet-only, multi-label prediction pipeline built on NHANES 24-hour dietary recall data. The project trains multiple neural network models, combines them via per-label stacking, applies per-label probability calibration, and evaluates threshold-based decision metrics (including workload per 1,000 screened). Model explanations are provided using SHAP.

## Paper
**Diet-Only Multi-Label Prediction of Hypertension, Diabetes, and Thyroid Dysfunction Using a Calibrated Deep Learning Ensemble**  
Authors: Shahin Ghanbari, Elaheh Homayounvala, Sahar Al-Sudani

## Key idea (one paragraph)
Many prediction systems rely on clinical or demographic inputs that may be unavailable. This work evaluates whether *diet-only* features (NHANES 24-hour recalls) can support multi-condition risk prediction using a multi-label deep learning pipeline. The system produces calibrated probabilities suitable for fixed, threshold-based decision policies and reports operational metrics such as precision/recall and alerts per 1,000 screened.

## Data
This project uses publicly available NHANES data:
- NHANES overview: https://www.cdc.gov/nchs/nhanes/about/index.html

**Important:** NHANES datasets are not included in this repository. You must download them from the CDC website and place them in the expected data directory structure.

## Repository structure
