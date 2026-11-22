# Activity 2: Logistic Regression – Binary Classification

## Overview

This project implements **Logistic Regression** to perform binary classification using the Iris dataset. The objective is to classify flowers into two categories: Setosa and Versicolor, based on their petal measurements.

## Dataset Information

- **Dataset:** Iris Dataset
- **Source:** [UCI Machine Learning Repository – Iris Dataset](https://archive.ics.uci.edu/dataset/53/iris)
- **Total Records:** 100
- **Selected Features:** 2
- **Target Variable:** Flower Class
- **Classes:**
  - `0` – Setosa
  - `1` – Versicolor

### Input Features

1. Petal Length (cm)
2. Petal Width (cm)

The original Iris dataset contains three flower classes. For this experiment, only Setosa and Versicolor were selected to create a binary classification problem.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Implementation Steps

1. Load and understand the Iris dataset.
2. Select two flower classes: Setosa and Versicolor.
3. Perform data inspection and statistical analysis.
4. Check missing values and duplicate records.
5. Visualize the class distribution.
6. Split the dataset into training and testing sets using an 80:20 ratio.
7. Apply feature scaling using StandardScaler.
8. Understand and visualize the Sigmoid Function.
9. Train the Logistic Regression model.
10. Predict flower classes and calculate probabilities.
11. Evaluate the model using a confusion matrix and classification metrics.
12. Plot the ROC curve and calculate ROC-AUC.
13. Compare the model with a baseline classifier.
14. Analyze different classification thresholds.

## Model Configuration

| Parameter | Value |
|---|---|
| Algorithm | Logistic Regression |
| Test Size | 20% |
| Training Size | 80% |
| Random State | 42 |
| Feature Scaling | StandardScaler |
| Classification Threshold | 0.5 |

## Model Results

The model produced the following results on the test dataset:

| Evaluation Metric | Score |
|---|---:|
| Accuracy | 1.00 (100%) |
| Precision | 1.00 (100%) |
| Recall | 1.00 (100%) |
| F1-Score | 1.00 (100%) |
| ROC-AUC | 1.00 |

### Confusion Matrix

| Actual / Predicted | Setosa | Versicolor |
|---|---:|---:|
| Setosa | 10 | 0 |
| Versicolor | 0 | 10 |

All 20 test records were classified correctly.

### Baseline Comparison

| Model | Accuracy |
|---|---:|
| Majority-Class Baseline | 50% |
| Logistic Regression | 100% |

## Conclusion

Logistic Regression was successfully implemented for binary classification using the Iris dataset. The model achieved 100% accuracy on the test dataset and performed better than the majority-class baseline.

This experiment demonstrates how Logistic Regression uses numerical features and the Sigmoid Function to calculate probabilities and classify data into two categories.

**Limitation:** The dataset is small, and Setosa and Versicolor are relatively easy to distinguish using petal measurements. Therefore, these results may not represent performance on more complex real-world datasets.

## Faculty Reference

Faculty GitHub Profile: [https://github.com/complexiota](https://github.com/complexiota)

---

**Academic Activity:** CIE 2 – Activity 2  
**Topic:** Binary Classification using Logistic Regression
