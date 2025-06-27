# TEXT_EMOTION_CLASSIFICATION

# Emotion Detection from Text

This project predicts emotions from textual input using multiple machine learning models. It handles the complete ML pipeline: data preprocessing, class balancing, feature extraction, model training, evaluation, and inference.

---

## 📁 Files

- `ml_model.py` — Full pipeline code (cleaning, training, testing, and evaluation)
- `dataset.csv` — Dataset used for training/testing (18,000 training samples, 2,000 test samples)

---

## 🧠 Model Overview

The following models were trained and evaluated:
- Logistic Regression
- HistGradientBoostingClassifier (Scikit-learn)
- XGBoost
- LightGBM
- CatBoost

Class imbalance is handled using **SMOTE**. Feature extraction is done with **TF-IDF Vectorization**.

---

## 📊 Emotion Classes

The target variable is a multiclass emotion label:

| Label | Emotion              |
|-------|-----------------------|
| 0     | Sadness / Depression |
| 1     | Joy / Happiness      |
| 2     | Love / Romance       |
| 3     | Anger / Irritation   |
| 4     | Anxiety / Fear       |
| 5     | Surprise / Confusion |

---
