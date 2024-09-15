# Diabetes Classification Project

## Overview
This project aims to predict whether a patient has diabetes based on medical features. The dataset used is the Pima Indians Diabetes Dataset.

## Data Exploration
The dataset consists of 8 features including `Pregnancies`, `Glucose`, `BloodPressure`, etc. Correlation analysis showed that `Glucose` and `BMI` were the most significant predictors of diabetes.

## Model Selection
We used a Random Forest Classifier, which provided a good balance between interpretability and performance. 

## Model Performance
- **Accuracy**: Achieved an accuracy of 72% on the test set.
- **Confusion Matrix**: The confusion matrix shows that the model correctly predicted 77 true positives and 34 true negatives.
- **Classification Report**: The report indicates precision, recall, and F1 score for both classes.

## Conclusion
The Random Forest model effectively predicts diabetes with satisfactory accuracy. Future work may involve exploring other models like SVM or deep learning techniques.

## License
This project is licensed under the MIT License.
