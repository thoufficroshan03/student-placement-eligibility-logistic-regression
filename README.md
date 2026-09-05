# Student Placement Eligibility Prediction using Logistic Regression

## Project Overview

This project predicts whether a student is likely to meet a placement eligibility criterion using Logistic Regression.

## Objective

To build a binary classification model that predicts student placement eligibility based on academic and placement-related features.

## Dataset

The dataset contains 1,000 student records with six input features and one target variable.

### Features

- CGPA
- Attendance Percentage
- Coding Score
- Projects Completed
- Internship Months
- Backlogs

### Target

- 1 – Eligible
- 0 – Not Eligible

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Machine Learning Algorithm

Logistic Regression

## Model Evaluation

| Metric | Result |
|---|---:|
| Accuracy | 70.00% |
| Precision | 68.87% |
| Recall | 73.00% |
| F1 Score | 70.87% |
| ROC-AUC | 0.7873 |

## Confusion Matrix

- True Negative: 67
- False Positive: 33
- False Negative: 27
- True Positive: 73

## Project Workflow

1. Load dataset
2. Explore dataset
3. Check data quality
4. Preprocess data
5. Split training and testing data
6. Train Logistic Regression model
7. Generate predictions
8. Evaluate the model
9. Analyze confusion matrix
10. Interpret feature coefficients

## Conclusion

The Logistic Regression model achieved 70% accuracy and an ROC-AUC of 0.7873 on the test dataset. The project demonstrates the complete workflow of a binary classification problem using Logistic Regression.
