# LRI Mortality in West Africa: Machine Learning Analysis

## Overview
This repository contains the complete code and data for the study:  
*"Temporal Trends and Mortality Burden of Lower Respiratory Infections in West African Countries (2010–2023): A Global Burden of Disease Analysis"*

The study integrates:
- Unsupervised clustering of mortality trajectories (k‑means)
- Machine learning prediction (XGBoost) with SHAP interpretation
- Temporal SHAP and immune arm transition analysis
- COVID‑19 counterfactual and PM₂.₅ reduction scenarios
- Ensemble forecasting (Prophet, XGBoost, LightGBM, LSTM) to 2030

All analyses are fully reproducible.

## Repository structure
west-africa-lri-ml/
├── data/ # Cleaned dataset (CSV)
├── scripts/ # Analysis scripts (01–06)
├── results/ # Output CSV tables
├── figures/ # Publication‑ready figures
├── requirements.txt # Python dependencies
├── LICENSE # MIT license
└── README.md # This file
