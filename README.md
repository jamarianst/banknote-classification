# banknote-classification
# Banknote Authentication – Machine Learning Classifier

This project uses a dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/267/banknote+authentication) to build classifiers that distinguish between **authentic** and **forged** banknotes based on image statistics.

Originally completed as part of the CSCI 3360E course at the University of Georgia. The notebook has been modified for public viewing and portfolio purposes.

---

## 🧠 Problem Statement

Given a set of banknotes with extracted statistical features (like variance and entropy), train machine learning models to predict whether each note is real (class 1) or fake (class 0).

---

## 🛠️ Techniques Used

- **Data Cleaning and EDA**
  - Feature distributions
  - Scatter plot visualizations (class-wise)
- **Modeling**
  - k-Nearest Neighbors (k = 5 and k = 500)
  - Gaussian Naive Bayes
- **Evaluation**
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix
- **Comparison of models** in terms of overfitting/underfitting

---

## 📊 Dataset

- **Source:** UCI ML Repository  
  https://archive.ics.uci.edu/dataset/267/banknote+authentication
- **Attributes:**
  - `variance`
  - `skewness`
  - `curtosis`
  - `entropy`
  - `class` (0 = forged, 1 = authentic)

*Note: The dataset itself is not included in this repo per course policy. Please download it from the source above if you'd like to replicate this work.*

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/banknote-authentication-ml.git
   cd banknote-authentication-ml
