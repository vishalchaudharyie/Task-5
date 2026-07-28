# 🧠 AI/ML Task 5 – Ensemble Learning

## 📌 Project Overview

This project demonstrates the implementation and comparison of multiple machine learning classification algorithms using the **Breast Cancer Wisconsin Dataset** from Scikit-learn. The main objective is to evaluate the performance of **Ensemble Learning** techniques and compare them with a baseline model.

The notebook includes model training, evaluation, cross-validation, and hyperparameter tuning to identify the best-performing classifier.

---

## 🚀 Features

- Load and preprocess the Breast Cancer dataset
- Train a Logistic Regression baseline model
- Implement Random Forest Classifier
- Implement Gradient Boosting Classifier
- Compare model performance using evaluation metrics
- Perform 5-Fold Cross Validation
- Optimize Random Forest using GridSearchCV
- Display performance comparison in tabular format

---

## 📂 Dataset

**Dataset:** Breast Cancer Wisconsin Dataset

Source:
- Scikit-learn Built-in Dataset (`load_breast_cancer()`)

Dataset Information:
- 569 samples
- 30 numerical features
- Binary Classification
  - Malignant
  - Benign

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - GridSearchCV
  - Cross Validation
  - Pipeline
  - StandardScaler

---

## 📊 Models Implemented

### 1. Logistic Regression
- StandardScaler Pipeline
- Baseline Classification Model

### 2. Random Forest Classifier
- Ensemble Learning using Bagging
- Multiple Decision Trees

### 3. Gradient Boosting Classifier
- Ensemble Learning using Boosting
- Sequential Tree Learning

---

## 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Cross Validation Accuracy

---

## 🔍 Hyperparameter Tuning

Random Forest parameters optimized using **GridSearchCV**.

Parameters searched include:

- Number of Estimators
- Maximum Depth
- Minimum Samples Split
- Minimum Samples Leaf

---

## 📁 Project Structure

```
AI-ML-Task5-Ensemble-Learning/
│
├── AI-ML-Task5-Ensemble-Learning.ipynb
├── README.md
└── LICENSE
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/AI-ML-Task5-Ensemble-Learning.git
```

2. Navigate to the project

```bash
cd AI-ML-Task5-Ensemble-Learning
```

3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open Jupyter Notebook

```bash
jupyter notebook
```

5. Run all cells in the notebook.

---

## 📚 Learning Outcomes

- Understanding Ensemble Learning
- Comparing multiple classification algorithms
- Model evaluation techniques
- Cross Validation
- Hyperparameter tuning using GridSearchCV
- Building reproducible ML pipelines

---

## 📌 Future Improvements

- Add XGBoost and AdaBoost models
- Perform Feature Importance Analysis
- Save trained models using Joblib
- Deploy the best model with Flask or FastAPI
- Add interactive visualizations

---


This project is licensed under the MIT License.
