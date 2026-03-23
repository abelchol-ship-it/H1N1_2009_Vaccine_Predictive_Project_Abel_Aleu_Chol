# Targeting Trust: Predicting H1N1 Vaccination Drivers

**Author:** Abel Aleu Chol Garang  
**Course:** Data Science  
**Date:** March 2026  


## Project Overview
This project predicts H1N1 vaccine uptake using machine learning.

Using data from the **National 2009 H1N1 Flu Survey (NHFS)**, this project develops a **binary classification framework** to predict whether an individual will receive the H1N1 vaccine. By identifying key behavioral, demographic, and attitudinal drivers, this analysis provides actionable insights for public health preparedness.

> **Note:** If GitHub fails to render the notebook below, please use the link below to view the full 86-cell analysis:
> 
> [**View Notebook on NBViewer (Recommended)**](https://nbviewer.org/github/abelchol-ship-it/H1N1_2009_Vaccine_Predictive_Project_Abel_Aleu_Chol/blob/main/phase3_h1n1_vaccine_prediction_Abel_Aleu_Chol.ipynb)


## Tableau Dashboard
**Interactive Visual Insights**  
Explore the deep-dive Exploratory Data Analysis (EDA) and psychological drivers of vaccine hesitancy in the interactive dashboard.  

 **View the Tableau Dashboard Here:** (https://public.tableau.com/views/National2009H1N1FluVaccineSurvey/VaccineFlueSurvey?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


## Key Objectives
- **Predictive Modeling:** Build a classifier to distinguish vaccinated vs. non-vaccinated individuals.  
- **Feature Importance:** Rank the strongest predictors—from doctor recommendations to perceived vaccine efficacy.  
- **Strategic Insights:** Deliver a data-driven profile of vaccine-hesitant groups to improve outreach efficiency.  
- **Optimization:** Balance Precision and Recall to minimize missed immunization opportunities (False Negatives).  


## Tech Stack & Workflow
- **Data Handling:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn, Tableau  
- **Machine Learning:** Scikit-Learn (Logistic Regression, Decision Trees, Random Forest)  

**Process:**  
1. **Data Preparation:** Handled missing values via imputation and categorical encoding.  
2. **Modeling:** Compared baseline models against tuned classifiers using GridSearchCV.  
3. **Evaluation:** Prioritized ROC-AUC (> 0.80) and Recall (≥ 70%) for the vaccinated class.  


## Major Findings
- **The "Doctor Factor":** Physician recommendations were among the strongest predictors of vaccine uptake.  
- **Perception Matters:** Individual beliefs regarding vaccine effectiveness and personal risk (the "Fear Paradox") outweighed many demographic factors.  
- **Feature Drivers:** Top 15 features were dominated by psychological perceptions and clinical safety concerns rather than just socioeconomic status.  


## Repository Structure
- `phase3_h1n1_vaccine_prediction.ipynb` — Main analysis and modeling notebook  
- `data/` — Contains `training_set_features.csv` and `training_set_labels.csv`  
- `README.md` — Project documentation and executive summary  


## Ethical Note
This analysis complies with the **Public Health Service Act** and utilizes **anonymized data** from the National Center for Health Statistics (NCHS).  