🏦 Bank Customer Churn Prediction & Segmentation System

## 📌 Project Overview

This project focuses on analyzing bank customer data to:

- Predict customer churn (whether a customer will leave the bank)
- Segment customers into meaningful groups using clustering
- Compare Machine Learning (Random Forest) and Deep Learning (ANN) models
- Provide business insights for customer retention strategies

The goal is to simulate a real-world **data science pipeline used in banking/fintech industries**.

---

## 🎯 Business Problem

Banks lose significant revenue when customers leave.  
This project helps answer:

- Which customers are likely to churn?
- What are the key factors influencing churn?
- Can we group customers into meaningful segments?
- Which model performs better: ML or Deep Learning?

---

## 📂 Dataset

**Source:** Kaggle - Churn Modelling Dataset

**Target Variable:**

- `Exited` (1 = Customer left, 0 = Customer stayed)

---

## 🧠 Techniques Used

### 📊 Exploratory Data Analysis (EDA)

- Churn distribution analysis
- Feature relationships with churn
- Correlation heatmap

### 🧹 Data Preprocessing

- Label Encoding (Gender)
- One-Hot Encoding (Geography)
- Feature scaling (for ANN & Clustering)

### 👥 Customer Segmentation

- K-Means Clustering
- Optimal cluster selection using Silhouette Score
- PCA visualization for cluster interpretation

### 🌲 Machine Learning Model

- Random Forest Classifier
- Feature importance analysis
- Confusion matrix evaluation

### 🧠 Deep Learning Model

- Artificial Neural Network (ANN)
- Batch Normalization
- Dropout Regularization
- Early Stopping

### 📈 Model Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score

---

## 📊 Model Comparison

Both models were compared using multiple evaluation metrics to ensure fair performance analysis.

Final comparison results are stored in:

reports/model_comparison.csv

---

## 🏆 Key Results

- Random Forest provides strong interpretability via feature importance
- ANN captures complex non-linear relationships
- Clustering reveals hidden customer groups
- Best clusters found using Silhouette Score = 3

---

## 📁 Project Structure

```text
Bank-Customer-Churn-Prediction/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Data_Preprocessing.ipynb
│   ├── 03_Customer_Segmentation.ipynb
│   ├── 04_Random_Forest_Model.ipynb
│   ├── 05_ANN_Model.ipynb
│   └── 06_Model_Comparison.ipynb
├── models/
│   ├── random_forest.pkl
│   └── ann_model.h5
├── reports/
│   ├── churn_distribution.png
│   ├── pca_clusters.png
│   ├── random_forest_confusion_matrix.png
│   ├── ann_confusion_matrix.png
│   ├── random_forest_metrics.csv
│   ├── ann_metrics.csv
│   └── model_comparison.csv
├── .gitignore
├── README.md
└── requirements.txt

---

## 🚀 How to Run This Project

### 1. Clone repository

```bash
git clone https://github.com/faizan-mustafa-dev/bank-churn-project.git
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run notebooks step-by-step

Start from:

01_EDA.ipynb

---

## 📌 Key Learnings

- End-to-end machine learning pipeline design
- Supervised vs Unsupervised learning
- Model evaluation and comparison
- Real-world business problem solving
- Deep learning implementation using ANN

---

## 📈 Future Improvements

- Hyperparameter tuning (GridSearchCV)
- Deployment using Streamlit
- Model explainability using SHAP dashboard
- API deployment (Flask/FastAPI)

---

## 👨‍💻 Author

Faizan Mustafa

Aspiring Data Scientist  
Focused on Machine Learning, Deep Learning & Real-world Projects

---

⭐ If you like this project

Give it a star ⭐ on GitHub and feel free to connect!
