# Heart Disease Prediction using Decision Tree and Random Forest

## Objective
Train and evaluate tree-based models to classify presence of heart disease.

## Dataset
- **Source**: Heart Disease Dataset
- **Target**: `target` column (1 = Disease, 0 = No Disease)

## Tools Used
- Scikit-learn (DecisionTreeClassifier, RandomForestClassifier)
- matplotlib, seaborn
- Metrics: Accuracy, Classification Report, Confusion Matrix, Cross-Validation

## Results
- Visualized decision tree
- Random forest gave higher accuracy than a single decision tree
- Most important features identified (e.g., `cp`, `thalach`, `oldpeak`)
