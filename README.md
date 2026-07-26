# 🫀 Heart Disease Prediction using Deep Learning, TabNet and XGBoost

An end-to-end Machine Learning and Deep Learning project for heart disease prediction using advanced preprocessing techniques, data balancing methods, explainable AI, and multiple predictive models.

---

## 📌 Project Overview

Heart disease remains one of the leading causes of death worldwide. Early prediction can significantly improve diagnosis and treatment decisions.

This project investigates the impact of different data balancing techniques on heart disease prediction using both Machine Learning and Deep Learning models.

The project compares several approaches including:

- Deep Multi-Layer Perceptron (MLP)
- 1D Convolutional Neural Network (1D-CNN)
- TabNet
- XGBoost

Different oversampling strategies are evaluated:

- Original Dataset
- SMOTE
- ADASYN
- DeepSMOTE (Autoencoder + SMOTE)

The project also incorporates Explainable AI (SHAP) to interpret the predictions of the best-performing model.

---

# 📂 Dataset

Dataset:
Heart Disease Dataset

Features include:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak
- ST Slope
- Number of Major Vessels
- Thalassemia

Target:

- 0 → No Heart Disease
- 1 → Heart Disease

---

# 🔄 Data Preprocessing

The preprocessing pipeline includes:

✔ Missing value imputation

- Median Imputation
- Most Frequent Imputation
- KNN Imputation

✔ Categorical Encoding

✔ Outlier Treatment

✔ Feature Scaling using StandardScaler

✔ Train/Test Split

---

# ⚖️ Handling Class Imbalance

To improve classification performance, three balancing strategies were investigated.

## SMOTE

Synthetic Minority Over-sampling Technique

## ADASYN

Adaptive Synthetic Sampling

## DeepSMOTE

A latent-space oversampling strategy based on:

Autoencoder

↓

Latent Representation

↓

SMOTE

↓

Decoder Reconstruction

---

# 🤖 Models

## Deep Learning

- Deep MLP
- 1D Convolutional Neural Network (1D-CNN)

## Machine Learning

- XGBoost

## Attention-based Network

- TabNet

---

# 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Matthews Correlation Coefficient (MCC)
- ROC-AUC Score

---

# 📈 Explainable AI

SHAP (SHapley Additive exPlanations) was used to interpret the predictions of the best-performing model.

Generated visualizations include:

- SHAP Summary Plot
- SHAP Feature Importance (Bar Plot)

---

# 🛠 Technologies

Python

TensorFlow / Keras

Scikit-learn

XGBoost

PyTorch-TabNet

SHAP

Pandas

NumPy

Matplotlib

Seaborn

Imbalanced-learn

---

# 📁 Project Structure

```
Project
│
├── Data
│
├── Data Preprocessing
│
├── Missing Values
│
├── Feature Engineering
│
├── SMOTE
│
├── ADASYN
│
├── DeepSMOTE
│
├── Deep MLP
│
├── 1D-CNN
│
├── TabNet
│
├── XGBoost
│
├── SHAP Explainability
│
└── Results
```

---

# 🚀 Installation

```bash
git clone https://github.com/your_username/Heart-Disease-Prediction.git

cd Heart-Disease-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run

Open the notebook

```
Projet Deep Learning.ipynb
```

Run all cells sequentially.

---

# 📊 Experimental Workflow

```
Dataset
      │
      ▼
Preprocessing
      │
      ▼
Feature Scaling
      │
      ▼
Balancing
(SMOTE / ADASYN / DeepSMOTE)
      │
      ▼
Model Training
      │
      ├── Deep MLP
      ├── 1D-CNN
      ├── TabNet
      └── XGBoost
      │
      ▼
Evaluation
      │
      ▼
SHAP Explainability
```

---

# 🌟 Key Features

- Complete preprocessing pipeline
- Multiple oversampling strategies
- DeepSMOTE implementation
- Comparison of Deep Learning and Machine Learning models
- Explainable AI with SHAP
- Multiple evaluation metrics
- Reproducible experiments

---

# 🔮 Future Work

- Hyperparameter optimization
- Cross-validation
- Ensemble learning
- Transformer-based tabular models
- External clinical datasets
- Model deployment using Streamlit or Flask

---

# 👨‍💻 Author

Oussama Ghajdaoui Alaoui

Master's Student in Intelligent Systems 

Artificial Intelligence • Machine Learning • Deep Learning • Data Science
