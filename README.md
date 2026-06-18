# Titanic Survival Prediction using Machine Learning

## Project Overview

This project predicts whether a Titanic passenger survived or not using multiple supervised machine learning algorithms.

The main goal of this project is to compare different ML models and evaluate their performance using accuracy, confusion matrix, classification report, and model comparison.

## Dataset

The dataset contains Titanic passenger details such as:

- Passenger Class
- Sex
- Age
- Fare
- Embarked
- SibSp
- Parch

Target column:

- Survived
  - 0 = Not Survived
  - 1 = Survived

## Steps Performed

1. Data loading
2. Data cleaning
3. Missing value handling
4. Encoding categorical columns
5. Train-test split
6. Feature scaling for KNN and SVM
7. Model training
8. Model evaluation
9. Model comparison

## Models Used

- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors
- Gaussian Naive Bayes
- Support Vector Machine

## Model Performance

| Model | Accuracy |
|---|---:|
| Random Forest | 82.68% |
| KNN | 82.12% |
| SVM RBF | 81.56% |
| Naive Bayes | 77.65% |
| Decision Tree Gini | 75.41% |
| Decision Tree Entropy | 74.86% |

## Best Model

Random Forest performed best with an accuracy of approximately **82.68%**.

## Conclusion

Random Forest achieved the highest accuracy because it combines multiple decision trees using ensemble learning and reduces overfitting compared to a single Decision Tree.

KNN and SVM also performed well after feature scaling. Naive Bayes performed moderately due to its feature independence assumption.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook