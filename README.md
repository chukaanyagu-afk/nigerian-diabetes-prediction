# nigerian-diabetes-prediction
Machine learning project comparing Decision Tree and Random Forest classifiers on a Nigerian diabetes dataset.
# Nigerian Diabetes Prediction Using Machine Learning

## Project Overview

This project explores the application of machine learning to diabetes-related data using a Nigerian diabetes dataset. It implements and compares two supervised learning algorithms: Decision Tree and Random Forest.

The objective is to investigate how these models learn patterns from the available data and evaluate their ability to predict the target outcome.

## Problem Statement

Diabetes is an important public health concern. Data analysis and machine learning can help researchers investigate patterns associated with diabetes in a dataset.

This project demonstrates a practical machine learning workflow for healthcare-related classification. The model is intended for educational and analytical purposes, not for clinical diagnosis.

## Objectives

- Explore and prepare the diabetes dataset.
- Build a Decision Tree classifier.
- Build a Random Forest classifier.
- Evaluate and compare model performance.
- Interpret the findings and limitations

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Methodology

1. Load and inspect the dataset.
2. Explore the features and target variable.
3. Handle missing values and prepare the data where necessary.
4. Split the data into training and testing sets.
5. Train Decision Tree and Random Forest classifiers.
6. Generate predictions on the test data.
7. Evaluate and compare the models.

## Model Evaluation

The models are evaluated using the metrics calculated in the notebook.

| Metric | Decision Tree | Random Forest |
|---|---|---|
| Accuracy | [100] | [100] |
| Precision | [1.00] | [1.00] |
| Recall | [1.00] | [1.oo] |
| F1-score | [1.00] | [1.00] |

## Key Findings

- Best-performing model: both model performed well despite it being modelled  solely on test data rather thann real data
- Main observation: if accurate data was used for the model, a more precise metrics would've been observed 
- Model comparison: I used both algorithms on the same diabetes dataset to compare a single weak learner(decision tree) versus an ensemble of learners(random forest)and demonstrate how ensemble learning solves overfiittng in medical diagnosis,but due to lack of accurate data no real comparison can be made

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run the cells in sequence.

Install the commonly used dependencies with:

`pip install pandas numpy matplotlib seaborn scikit-learn jupyter`

## Limitations

Model performance depends on the quality, size, representativeness, and preparation of the dataset. Results from this dataset should not automatically be generalized to the Nigerian population.

This project is not a substitute for professional medical assessment.

## Conclusion

This project demonstrates the implementation and comparison of Decision Tree and Random Forest classifiers on diabetes-related data. It provides practical experience in data preparation, supervised learning, model evaluation, and interpreting healthcare-related datasets.



## Project Type

Supervised Machine Learning | Binary Classification (if applicable)
