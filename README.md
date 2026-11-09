# Machine Learning Foundations

## Project Overview

This project demonstrates the use of machine learning classification models to predict whether a student will pass or fail based on selected student performance features.

Two classification models were trained and compared:

- Logistic Regression
- Decision Tree

## Dataset

The project uses the Student Performance dataset.

The dataset contains information about students, including age, study time, previous failures, absences, and academic grades.

The final grade (`G3`) was used to create a binary target:

- **Pass:** G3 ≥ 10
- **Fail:** G3 < 10

## Features Used

The following features were selected for the models:

- Age
- Study time
- Previous failures
- Absences
- G1
- G2

## Machine Learning Process

The project followed these steps:

1. Loaded and inspected the dataset.
2. Created a binary pass/fail target variable.
3. Selected relevant features.
4. Split the data into 80% training and 20% testing sets.
5. Trained a Logistic Regression model.
6. Trained a Decision Tree model.
7. Evaluated both models using accuracy, confusion matrices, and classification reports.
8. Compared the performance of both models.

## Models

### Logistic Regression

Logistic Regression was used as a baseline classification model for predicting student pass or fail outcomes.

### Decision Tree

A Decision Tree classifier was used to identify patterns in the selected student features and classify students into pass or fail categories.

## Evaluation

The models were evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report

Both models used the same training and testing split to provide a fair comparison.

## Results

The project includes the following results:

- Model accuracy comparison chart
- Logistic Regression confusion matrix
- Decision Tree confusion matrix
- Classification reports in the notebook

The model comparison is based on the test-set accuracy obtained during the experiment.

## Project Structure

```text
machine_learning_foundations
│
├── data
│   └── student-mat.csv
│
├── notebooks
│   └── machine_learning.ipynb
│
├── results
│   ├── model_accuracy_comparison.png
│   ├── logistic_confusion_matrix.png
│   └── decision_tree_confusion_matrix.png
│
├── .gitignore
├── README.md
├── modelcard.md
└── requirements.txt
```

## Requirements

The project uses Python and the following libraries:

- pandas
- numpy
- matplotlib
- scikit-learn
- jupyter

Install the required packages using:

```bash
pip install -r requirements.txt
```

## How to Run

1. Open the project folder in VS Code.
2. Activate the Python virtual environment.
3. Open `notebooks/machine_learning.ipynb`.
4. Select the appropriate Python kernel.
5. Run the notebook cells from top to bottom.
6. Review the model results and charts in the `results` folder.

## Model Card

Additional information about the models, dataset, intended use, limitations, and ethical considerations is available in `modelcard.md`.

## Conclusion

This project demonstrates the basic machine learning workflow of preparing data, training classification models, evaluating their performance, and comparing their results.

The project was developed for educational purposes as part of the Machine Learning Foundations curriculum.