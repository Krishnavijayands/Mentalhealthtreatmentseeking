# Predicting Treatment-Seeking Behaviour for Workplace Mental Health Using Machine Learning  

## Project Overview  
This repository contains the code, results, and documentation for my MSc Data Science dissertation project at the **University of Hertfordshire**.  

The project investigates the use of **machine learning models** to predict whether employees in the technology sector are likely to seek treatment for mental health conditions.  

The study is based on the **Open Sourcing Mental Illness (OSMI) 2014 Mental Health in Tech Survey**, which captures demographic, personal, and workplace factors associated with mental health.  

Three research questions structured the investigation:  

- **RQ1** - Which model provides the best predictive performance for treatment-seeking behaviour (Logistic Regression, Random Forest, Neural Network)?  
- **RQ2** - Does reducing the feature space to the top fifteen predictors (via permutation importance) preserve predictive performance while improving interpretability?  
- **RQ3** - Which subgroups are most often misclassified, and what does this reveal about potential fairness issues?  

## Repository Structure  

This repository contains the **full workflow** for the dissertation project.  
The dataset is uploaded to ensure **reproducibility** of all experiments.  

### Files and Notebooks  

1. **`Mental Health in Tech - EDA(1).ipynb`**  
   - Contains the **Exploratory Data Analysis (EDA)**.  
   - Includes descriptive statistics, visualisations of key demographic and workplace variables, and initial insights into treatment-seeking behaviour.  
   - Provides the foundation for understanding data distribution, handling missing values, and informing preprocessing decisions.  

2. **`Mental Health in Tech - 23083552.ipynb`**  
   - Contains the **main analysis pipeline**.  
   - Covers preprocessing, feature engineering, model training, hyperparameter tuning, evaluation, feature reduction (RQ2), and subgroup fairness/error analysis (RQ3).  
   - Includes all optimisation experiments, threshold adjustments, and performance comparisons across Logistic Regression, Random Forest, and Neural Network models.  

3. **`survey.csv`**  
   - The **OSMI Mental Health in Tech Survey (2014)** dataset used for all analyses in this project.  
   - Provided under a **Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0)** licence.  

## Key Findings  

- **RQ1:** Logistic Regression and Random Forest outperformed the Neural Network at default thresholds.  
- **RQ2:** Reducing to the top 15 features preserved predictive performance and improved interpretability.  
- **RQ3:** Subgroup analysis revealed fairness concerns, with misclassifications concentrated among males, employees in large companies, and those with unclear workplace benefits.  

## Licence  

This repository uses the **OSMI Mental Health in Tech Survey (2014)** dataset, provided under the **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)** licence.  




