# Titanic Survival Prediction

This project predicts survival of Titanic passengers using machine learning.

## Dataset
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- Train.csv: contains 891 passengers with target 'Survived'
- Test.csv: 418 passengers without target

## Features
- Categorical: Sex, Pclass, Embarked, Cabin (first letter), Title
- Numerical: Age, Fare, SibSp, Parch, FamilySize
- Additional features: IsAlone, Title

## Preprocessing
- Fill missing Age/Fare with median
- Fill missing Embarked with mode
- Cabin simplified to first letter
- One-hot encoding for categorical features

## Models
- Logistic Regression
- Decision Tree
- Random Forest

## Submission
- `submission.csv` contains predictions for the test set.
