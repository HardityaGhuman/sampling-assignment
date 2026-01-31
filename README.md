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

## Results Table

| Model | Sampling1 (ROS) | Sampling2 (SMOTE) | Sampling3 (RUS) | Sampling4 (SMOTETomek) | Sampling5 (SMOTEENN) |
|------|-----------------|-------------------|-----------------|------------------------|----------------------|
| M1 (Logistic Regression) | 90.97 | 91.61 | 58.06 | 91.61 | 90.32 |
| M2 (KNN) | 96.13 | 94.19 | 65.81 | 94.19 | 91.61 |
| M3 (Decision Tree) | 99.35 | 96.13 | 50.97 | 96.77 | 87.74 |
| M4 (Random Forest) | 99.35 | 99.35 | 63.87 | 99.35 | 98.71 |
| M5 (SVM) | 94.84 | 95.48 | 41.94 | 95.48 | 94.19 |

## Results Summary
Oversampling based techniques (SMOTE, Random Oversampling, SMOTETomek) consistently improved performance across most models. Random Undersampling resulted in loss of information and poor accuracy.

Random Forest combined with oversampling techniques achieved the highest accuracy (~99%).

## Conclusion
Sampling techniques play a crucial role in handling imbalanced datasets. Ensemble and tree based models benefit significantly from oversampling methods.