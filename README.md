# Cirrhosis Patient Survival Prediction - Multi-Class Classification

Advanced machine learning system predicting cirrhosis patient outcomes using ensemble methods, gradient boosting, and SMOTE balancing techniques.

## Project Overview

Clinical decision support system that predicts survival status for cirrhosis patients based on demographic, clinical, and laboratory measurements. Compares multiple machine learning algorithms with comprehensive feature engineering and class imbalance handling.

## Key Features

- Multi-Class Classification (3 outcome categories)
- Ensemble Methods (Random Forest, XGBoost)
- Advanced Preprocessing (SimpleImputer, StandardScaler)
- Hyperparameter Optimization via GridSearchCV
- SMOTE Oversampling for minority class handling
- Dual Feature Importance (gain-based and permutation)
- Stratified K-Fold Validation for robust evaluation

## Dataset

- Size: 418 patients
- Features: 17 clinical measurements
- Target: Patient status (C: Censored-alive 55.5%, CL: Liver transplant 6.0%, D: Death 38.5%)
- Challenge: Severe minority class (CL only 6%)

## Technologies

- Python 3.8+
- scikit-learn
- XGBoost
- imbalanced-learn (SMOTE)
- pandas/numpy
- matplotlib/seaborn

## Results

XGBoost Optimized achieved ~85% accuracy and 0.83 F1-score with best generalization.

## License

MIT License - educational purposes
