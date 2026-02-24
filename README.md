# Deep-Learning
This Repo contains all of my Deep learning projects
<br>
# Perceptron Classification on Iris Dataset

## Project Overview
This project demonstrates a simple binary classification using the Perceptron algorithm from scikit-learn.

We use the Iris dataset and convert it into a binary classification problem:
- Class 0 → Setosa
- Class 1 → Not-Setosa (Versicolor & Virginica)

The model is trained and evaluated using accuracy and a classification report.

---

## Dataset
Dataset used: Iris Dataset (built-in from scikit-learn)

Features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target:
- Original classes: 0, 1, 2
- Converted to binary: 0 (Setosa) vs 1 (Not-Setosa)

---

## Steps Performed

1. Load Iris dataset
2. Convert multi-class to binary classification
3. Split into training and testing sets (70% train, 30% test)
4. Standardize features using StandardScaler
5. Train Perceptron model
6. Make predictions
7. Evaluate using accuracy and classification report

---

## Model Details

Algorithm: Perceptron  
Parameters:
- max_iter = 10000
- eta0 = 0.01
- random_state = 1

---

## Evaluation Metrics

- Training Accuracy
- Test Accuracy
- Precision
- Recall
- F1-score

---

## How to Run

1. Install required libraries:

```bash
pip install numpy scikit-learn
