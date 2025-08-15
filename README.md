# Customer Churn Prediction with TabNet and CatBoost

This repository contains the implementation of the **AIDI 1002 Final Project** on predicting customer churn using the **Telco Customer Churn dataset**.

## Overview
- Baseline: **TabNet**
- Contribution: **CatBoost** comparison + **SHAP** interpretability
- Metrics: Accuracy, F1, ROC-AUC

## Files
- `AIDI1002_TabNet_Churn_Final.ipynb` (and/or `(1).ipynb`) – main notebook
- `requirements.txt` – Python dependencies
- `.gitignore` – ignore notebook checkpoints, data, etc.
- `LICENSE` – MIT License
- `snippets.md` – optional upgrade cells (threshold tuning, proper ROC-AUC, quick TabNet grid, reproducibility)

## Dataset
Telco Customer Churn – https://www.kaggle.com/datasets/blastchar/telco-customer-churn
(Mirror used inside the notebook to avoid Kaggle auth.)

## Paper & Code
- TabNet paper (2019): https://arxiv.org/abs/1908.07442
- PyTorch TabNet repo: https://github.com/dreamquark-ai/tabnet
