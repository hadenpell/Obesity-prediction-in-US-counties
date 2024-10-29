## Background

This project looks at how socioeconomic factors can be used to predict obesity risk in US counties. Obesity prevalence for every US county was provided and was classified as either low, moderate, or high depending on calculated binning criteria.
Hypotheses about the best and worst correlated socioeconomic factors with obesity prevalence were explored and results reported. 3 supervised machine-learning classification models were used and evaluated for their performance with the dataset (KNN, GaussianNB, and Decision Trees). 
A hypothesis about the best model for the dataset was explored and results reported.

The best parameters for each machine learning model were determined with GridSearchCV. Each tuned model’s performance using a cross-validation and percentage-split approach was calculated.
Comparisons between tuned vs untuned model performance revealed each model’s test set score when trained with our dataset. K-Nearest-Neighbors had the highest performance on our dataset.

## Code

Source code, analysis and results as well as documentation can be found in **Obesity-Prediction.ipynb.** Data is found in datasets folder, including
raw data and clean data.

## Visualizations

PNG formatted visualizations created in the notebook can be found in the main folder, including a feature r correlations to target chart (feature-corr.png),
a comparison of model performances (model-performance.png) and a scatter matrix plotting the top 5 features against each other (scatter-matrix.png).
