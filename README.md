# Divya-S---Insurance-Claim-Severity-Prediction-Project
Insurance Claim Severity Prediction — SHAP Analysis

This project builds an advanced gradient boosting model (XGBoost) to predict insurance claim severity and uses SHAP (Shapley Additive Explanations) for global and local interpretability.
The goal is to understand which policyholder and vehicle features drive risk and claim severity.

Project Contents

Insurance_Claim_Severity_Predictions_project_.ipynb

Full code for:

Model training

RandomizedSearchCV tuning

Predictions

Global SHAP summary + feature importance

3 local SHAP case studies

task1_expected_deliverable.txt
Trained model configuration parameters.

task2_expected_deliverable.txt
Python code explanation for training, prediction, and SHAP analysis.

task3_expected_deliverable.txt
Global SHAP interpretation (top 5 features).

task4_expected_deliverable.txt
Local SHAP case study analysis.

task5_expected_deliverable.txt
Model biases and unexpected behaviors.

plots/ folder
Contains:

shap_summary_bar.png

shap_summary_beeswarm.png

dependence plots

local force plots (top, low, outlier)

Dataset

insurance_claims_large.csv
Used for model training and SHAP computations.

Conclusion

SHAP helped identify risk-driving features such as vehicle age, policyholder age, and vehicle value. This improves transparency and supports responsible decision-making in insurance workflows.
