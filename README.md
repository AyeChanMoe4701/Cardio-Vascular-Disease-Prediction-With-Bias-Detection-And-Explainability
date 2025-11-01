#  Fairness in Cardiovascular Disease Prediction Models

This repository contains the implementation and analysis for the MSc research project **"Fairness in Cardiovascular Disease Prediction Models"**. The study focuses on evaluating bias, explainability, and predictive performance in machine learning models used for cardiovascular disease (CVD) prediction. The project compares **Logistic Regression**, **Random Forest**, and **XGBoost** models using fairness-aware evaluation metrics and **SHAP**-based interpretability methods.

---

##  Project Overview

The project investigates algorithmic fairness and model transparency in healthcare prediction systems. Cardiovascular diseases remain a leading cause of global mortality, and predictive models can support early detection and intervention. However, biases in data and algorithms can lead to unequal treatment outcomes across demographic groups. This research aims to:

- Develop predictive models for cardiovascular disease classification.
- Evaluate **bias and fairness** across gender and age groups.
- Apply **SHAP explainability** to interpret model decisions.
- Compare models on both **accuracy** and **equity** criteria.

---

##  Methodology

The analysis follows a structured, empirical workflow:

1. **Data Preprocessing**
   - Cleaning and feature encoding of the cardiovascular dataset.
   - Splitting into training and testing sets.
2. **Model Training**
   - Logistic Regression  
   - Random Forest  
   - XGBoost
3. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
4. **Fairness Analysis**
   - Group fairness evaluation (gender, age)
   - Metrics: Statistical Parity Difference, Equal Opportunity, Disparate Impact
5. **Explainability**
   - Model interpretability using **SHAP (SHapley Additive exPlanations)**.
   - Visualization of feature importance and decision impact.

---

##  Dataset

The dataset used is the **Cardiovascular Disease Dataset** (publicly available from Kaggle / UCI Repository).  
It includes patient-level information such as:
- Demographics (Age, Gender)
- Medical indicators (Blood Pressure, Cholesterol, BMI)
- Lifestyle factors (Smoking, Alcohol intake, Physical activity)
- Disease presence (binary target variable)

> Data preprocessing ensures ethical handling and balanced representation.

