# MLHC Final Project 2023
This repository contains the final project of the MLHC-2023 course completed by Gal Bodek and Keren Danan.
In this project, we aimed to predict mortality and classify sepsis patients enrolled in the PROVIDE clinical trial using both clinical data and 
Olink proteomics data. 

This repository contains multiple files: 

1- Preprocessing.ipynb : This notebook contains data preprocessing steps and data analysis.

2- Model.ipynb: This notebook contains the code for training the models and evaluating them.

4- Data Analysis directory: This directory contains a variety of data exploratory plots, including data distribution plots, Kaplan-Meier survival analysis for clinical data, and plots describing missing data rates.

5- Evaluation directory: This directory contains basic metric plots related to the mortality prediction models, SHAP (Shapley Additive Explanations) values for the Random Forest model, and feature importance based on Random Forest MDI.

6- Feature Selection for Classification directory:  This directory is dedicated to the feature selection process. It includes Cox proportional hazards regression survival analysis, divided into two parts: results for clinical features and results for Olink features.

7- Endotypes directory: This directory contains plots regarding the second classification model

8 - requirements.txt: specifying required libraries

For further information you can contact us by mail: galbodek@mail.tau.ac.il, kerendanan1@mail.tau.ac.il
