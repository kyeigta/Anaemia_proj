# Anaemia Prediction Project

This repository contains machine learning workflows and experimental frameworks dedicated to the non-invasive or predictive detection of anemia. By leveraging clinical data and patient risk factors, this project aims to evaluate and deploy optimized predictive models to aid in early diagnosis.

---

## 🚀 Notebooks Overview

*   **`Anemia_Prediction_ensemble.ipynb`**
    *   **Focus:** Ensemble Learning Approaches.
    *   **Description:** This notebook implements an ensemble-based machine learning pipeline (such as Random Forests, Gradient Boosting, Voting, or Stacking Classifiers) to maximize classification accuracy, sensitivity, and specificity in predicting anemia. It covers exploratory data analysis (EDA), data scaling/preprocessing, feature importance tracking, and model evaluation metrics (Confusion Matrix, ROC-AUC curves).

---

## 🛠️ Typical Workflow

1.  **Exploratory Data Analysis (EDA):** Visualizing key hematological indicators, demographic distributions, and correlation matrices to identify strong predictors.
2.  **Data Preprocessing:** Handling missing values, handling class imbalances (e.g., SMOTE if applicable), and scaling features to prepare data for training.
3.  **Ensemble Modeling:** Combining the predictive power of multiple base estimators to minimize variance, reduce bias, and improve overall generalization on unseen test datasets.
4.  **Evaluation:** Metrics tracking focusing heavily on recall/sensitivity to minimize false negatives—a critical requirement in medical diagnostics.

---

## ⚙️ Setup & Requirements

To clone this repository and run the notebook locally, ensure you have the following Python environment packages installed:

```bash
git clone [https://github.com/kyeigta/Anaemia_proj.git](https://github.com/kyeigta/Anaemia_proj.git)
cd Anaemia_proj
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
