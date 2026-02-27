# Spotify Track Classification 🎵

## 📌 Project Overview
This project explores how machine learning models can classify Spotify tracks based on their audio features.

The objective is to predict whether a song belongs to a target category using features such as:

- Energy
- Danceability
- Valence
- Tempo


## ⚙️ Models Implemented
- Logistic Regression
- Random Forest Classifier
  

## 🧪 Methodology
- Train-test split
- Handling class imbalance using `class_weight="balanced"`
- Model evaluation using:
  - Accuracy
  - Precision / Recall / F1-score
  - Confusion Matrix
- Feature importance analysis


## 📊 Key Findings
- Random Forest outperformed Logistic Regression.
- Random Forest improved recall on the minority class.
- Energy and Tempo were the most influential features.


## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn


## 🚀 What I Learned
- Basic workflow of a machine learning classification project
- How to evaluate models beyond accuracy
- The importance of handling class imbalance
