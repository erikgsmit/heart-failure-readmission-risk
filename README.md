# Heart Failure Readmission Risk Prediction

This project builds an end-to-end machine learning pipeline to predict 30-day hospital readmission risk for heart failure patients using clinical biomarkers, treatment variables, vital signs, and social determinants of health.

## Project Motivation

Hospital readmissions are costly and clinically important, especially among heart failure patients. This project explores whether combining clinical factors with social determinants of health can improve readmission risk prediction and make model outputs more interpretable.

Dataset: [Heart Failure Readmission & SDoH Dataset from Kaggle. :contentReference[oaicite:0]{index=0}](https://www.kaggle.com/datasets/nudratabbas/heart-failure-readmission-and-sdoh-dataset)

## Goals

- Predict 30-day readmission risk
- Compare clinical-only vs clinical + SDoH models
- Identify key readmission drivers using explainability methods
- Present results in a recruiter-friendly, reproducible format

## Methods

Models:

Evaluation:
- ROC-AUC
- Precision, recall, F1-score
- Confusion matrix
- Calibration curve

Explainability:
- Feature importance
- SHAP values
- Clinical vs social factor comparison

## Key Questions

1. Which factors are most associated with readmission?
2. Do social determinants improve prediction beyond clinical variables?
3. Can the model support interpretable risk stratification?

## Results

Add final metrics here after modeling.


## Repository Structure

Explain folders here.

## How to Run

```bash
git clone https://github.com/your-username/heart-failure-readmission-risk.git
cd heart-failure-readmission-risk
pip install -r requirements.txt
