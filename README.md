# Tibia Bone Classification – ML Project (RA in MIA Task 2)
This repository contains the code and documentation for a machine learning project focused on classifying tibia bone data using tabular features. 

### Project Summary
Binary classification task using medical tabular data

Three datasets: train, test, and blinded test

Built models with proper preprocessing, feature engineering, and evaluation

Final deliverables include class probability predictions and a 2-page methodology report

### Models Implemented
Logistic Regression

Random Forest

Support Vector Machine (SVM)

Stacking Classifier (combining all three)

### Evaluation Metrics
Accuracy

AUROC

Sensitivity (Recall)

Specificity

F1 Score

Evaluated using stratified k-fold cross-validation

### Preprocessing Steps
Handled missing values (median grouped by class)

Dropped low-variance features

Outliers capped at 99th percentile

Feature selection using Mutual Information

Dimensionality reduction using PCA (98% variance retained)

SMOTE tested but not used due to performance drop


