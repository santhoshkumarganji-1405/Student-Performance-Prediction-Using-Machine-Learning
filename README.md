# Student Performance Prediction Using Machine Learning

## Overview

This project focuses on predicting student academic performance using Machine Learning classification algorithms. The model analyzes various student-related factors and predicts whether a student is likely to pass or fail based on their academic scores.

The project demonstrates the complete Machine Learning workflow, including data preprocessing, feature engineering, model training, evaluation, and performance visualization.

---

## Project Objectives

- Understand supervised machine learning concepts.
- Perform data preprocessing and feature engineering.
- Train classification models using Decision Tree and Random Forest.
- Evaluate model performance using multiple metrics.
- Visualize results using Confusion Matrix and ROC Curve.
- Compare different machine learning algorithms.

---

## Dataset Information

The dataset contains student-related information such as:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

### Target Variable

A new feature called `average_score` is created using:

average_score = (Math Score + Reading Score + Writing Score) / 3

Students with an average score greater than or equal to 50 are classified as:

- 1 → Pass
- 0 → Fail

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Algorithms

### Decision Tree Classifier

Decision Tree is a supervised learning algorithm that uses a tree-like structure to make classification decisions.

### Random Forest Classifier

Random Forest is an ensemble learning technique that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## Project Workflow

1. Data Collection
2. Data Exploration
3. Data Preprocessing
4. Feature Engineering
5. Label Encoding
6. Train-Test Split
7. Decision Tree Model Training
8. Random Forest Model Training
9. Model Evaluation
10. Data Visualization

---

## Evaluation Metrics

### Accuracy Score

Measures the percentage of correctly predicted instances.

### Confusion Matrix

Shows:

- True Positives
- True Negatives
- False Positives
- False Negatives

### Classification Report

Includes:

- Precision
- Recall
- F1-Score
- Support

### ROC Curve

Measures the model's ability to distinguish between classes.

### AUC Score

Represents the overall performance of the classifier.

---

## Results

| Model | Accuracy |
|---------|---------|
| Decision Tree | 98.5% |
| Random Forest | 99.5% |

### Best Performing Model

Random Forest Classifier achieved the highest accuracy of **99.5%**.

---

## Visualizations

The project includes:

- Confusion Matrix Heatmap
- ROC Curve
- Model Performance Analysis

---

## Project Structure

Student-Performance-Prediction/
│
├── dataset/
│   └── StudentsPerformance.csv
│
├── images/
│   ├── confusion_matrix.png
│   └── roc_curve.png
│
├── student_performance_prediction.ipynb
├── README.md
├── requirements.txt
└── results/

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Student-Performance-Prediction.git
