# ABCD_project

**ABCD Data Analysis Project**

This repository contains the code for my project on the data from the Adolescent Brain Cognitive Development (ABCD) study. 
This project involved pre-processing the extensive ABCD dataset, applying the supervised learning algorithms, and data visualisation.



**Project Overview**

1. Data pre-processing.
- Extract variables and questionnaires required for analysis.
- Applied specific exclusion criteria to ensure the dataset met my research requirements.
- Dealing with NaN values
- Matching participants to ensure balanced classes
- Creating two different datasets, one including demographic and clinical data, the other neuroimaging data.

2. Supervised learning implementation
- Feature selection using ShapRFECV
- Implementing a Random Forest Classifier, Support Vector Machine and Logistic Regression
- Hyperparameter tuning

3. Visualization
- Of the performance metrics for each classifier and dataset
- Of the ROC-AUC for each classifier and dataset
- Of the Shap feature importance

  
**Repository Structure**

- 'preprocessing.ipynb': Jupyter Notebook containing the code for preprocessing the ABCD data and creating the required datasets.
- 'ML_pipeline_model1.ipynb': Jupyter Notebook containing the implementation of the feature selection, supervised learning algorithms
  and hyperparameter tuning for demographic and clinical data.
- 'ML_pipeline_model2.ipynb': Jupyter Notebook containing the implementation of the feature selection, supervised learning algorithms
  and hyperparameter tuning for the neuroimaging data.
- 'visualisations.ipynb': Jupyter Notebook containing the code for generating visualisations of the project results

  

Feel free to explore the notebooks to understand the data analysis process and findings.
If you have any questions, please don't hesitate to reach out. 
