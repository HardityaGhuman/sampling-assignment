# Sampling Techniques on Imbalanced Credit Card Dataset

## Objective
To study the impact of different sampling techniques on the performance of machine learning models for a highly imbalanced credit card fraud dataset.

## Dataset
The dataset contains 772 samples with severe class imbalance (only 1.16% fraud cases).

## Sampling Techniques Used
1. Random Oversampling
2. SMOTE
3. Random Undersampling
4. SMOTETomek
5. SMOTEENN

## Models Used
- Logistic Regression
- KNN
- Decision Tree
- Random Forest
- SVM

## Results Summary
Oversampling based techniques (SMOTE, Random Oversampling, SMOTETomek) consistently improved performance across most models. Random Undersampling resulted in loss of information and poor accuracy.

Random Forest combined with oversampling techniques achieved the highest accuracy (~99%).

## Conclusion
Sampling techniques play a crucial role in handling imbalanced datasets. Ensemble and tree based models benefit significantly from oversampling methods.