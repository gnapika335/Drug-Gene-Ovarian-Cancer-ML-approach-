# Drug-Gene-Ovarian-Cancer-ML-approach-
# Drug–Gene Interaction Prediction in Ovarian Cancer using Machine Learning

## Project Overview
This project explores the use of Machine Learning (ML) to predict drug–gene interactions with a focus on **drug sensitivity** in ovarian cancer.  
The aim is to identify biomarkers of drug response/resistance and contribute towards personalized cancer therapy.

##  Objectives
- Predict sensitivity of ovarian cancer cell lines to chemotherapeutic and targeted drugs.
- Identify gene expression patterns linked to drug resistance.
- Evaluate ML models (Logistic Regression, Random Forest, SVM, XGBoost, Deep Learning).

## Repo Structure
literature/ # Research papers & weekly summaries
datasets/ # Raw and processed datasets
notebooks/ # Colab/Jupyter notebooks
results/ # Model outputs, plots, metrics


##  Environment Setup
Main Python libraries used:
- `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- `xgboost`, `lightgbm`
- `rdkit` (for drug descriptors, optional)
- `biopython` (optional for biological data)
- `networkx`, `shap`

## Current Progress
- Environment setup completed (Colab + required libraries installed).
- Repo and folder structure created.
- Literature review: 6 papers summarized.
- Next step: download ovarian cancer gene expression and drug sensitivity data (TCGA-OV, GDSC).

## Workflow
- **Week 1:** Scope definition + literature review ✅
- **Week 2:** Environment setup + repo structure ✅
- **Week 3:** Dataset collection & preprocessing 🔜
- **Week 4:** Pilot ML experiment with baseline models

