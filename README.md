# Schizophrenia Mortality Risk Analysis

This project explores mortality risk factors in individuals with schizophrenia and intellectual disabilities. Using anonymised clinical records, it builds predictive models to identify high-risk patients and provides interpretable insights into which health indicators contribute most to patient outcomes.

---

## Objectives
- Analyse clinical data to uncover factors associated with patient mortality  
- Train machine learning models to predict mortality outcomes  
- Use SHAP values to interpret model decisions and assess feature importance  

---

## Dataset
The dataset consists of anonymised hospital records covering demographics, psychiatric and neurological diagnoses, medication usage, and review flags. It has been fully sanitised to remove any personally identifiable information.

📁 `mental_health_clinical_data.csv`

---

## Tools & Technologies
- Python (pandas, scikit-learn, XGBoost, SHAP, matplotlib, seaborn)  
- Jupyter Notebook

---

## Features
- Models: Logistic Regression, Random Forest (GridSearch), XGBoost, SVM (GridSearch)  
- Evaluation: ROC AUC, confusion matrix, classification report, cross-validation  
- Explainability: SHAP value visualisation and feature importance analysis  
- Preprocessing: Missing value handling, encoding, stratified splitting, feature scaling  

---

## Results & Insights
- High-risk indicators included polypharmacy, seizure patterns, and lack of regular reviews  
- Random Forest and XGBoost delivered strong classification performance  
- SHAP analysis provided clear interpretability of model outputs  

---

## Files Included
- `Schizophrenia_Mortality_Analysis.ipynb`: Complete and structured notebook  
- `mental_health_clinical_data.csv`: Cleaned and anonymised clinical dataset  
- `LICENSE`: MIT License  

---

## Future Enhancements
- Explore survival modelling techniques  
- Integrate comorbidity indices and time-series variables  
- Expand to multi-centre datasets if available
