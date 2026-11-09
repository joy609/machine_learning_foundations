# MODEL CARD

## Model Overview

This project uses two machine learning classification models to predict whether a student will pass or fail based on selected academic and demographic features.

The models used are:

- Logistic Regression
- Decision Tree Classifier

## Intended Use

The models are intended for educational analysis and learning purposes. They demonstrate how machine learning can be used to classify student performance.

The models should not be used as the sole basis for making decisions about individual students.

## Dataset

The dataset used is the Student Performance dataset.

The target variable was created from the student's final grade (`G3`):

- `1` = Pass (G3 ≥ 10)
- `0` = Fail (G3 < 10)

The features used were:

- Age
- Study time
- Previous failures
- Absences
- First-period grade (G1)
- Second-period grade (G2)

## Training and Testing

The dataset was divided into:

- 80% training data
- 20% testing data

A fixed random state of 42 was used so that the same train/test split could be reproduced.

## Evaluation

The models were evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report

Both models used the same training and testing data to ensure a fair comparison.

## Limitations

The model is based on a limited set of student-related features and may not capture all factors that influence academic performance.

The dataset is also used for educational demonstration and should not be interpreted as a complete representation of student success.

## Ethical Considerations

Predictions about students should be used carefully. Machine learning predictions can contain errors or reflect limitations in the data used to train the models.

The results should support analysis rather than replace human judgment.

## Conclusion

The Logistic Regression and Decision Tree models were successfully trained and evaluated. Their performance was compared using accuracy and confusion matrices to determine which model performed better on the test dataset.