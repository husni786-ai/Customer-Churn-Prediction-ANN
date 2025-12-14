# 🧠 Customer Churn Prediction using Artificial Neural Networks

This project implements an end-to-end Machine Learning solution for predicting customer churn (whether a customer will leave a service) using an **Artificial Neural Network (ANN)** built with TensorFlow/Keras. The pipeline includes data acquisition, extensive preprocessing, model construction, training, and performance visualization.

## 🎯 Project Goals

The main objective is to build a robust binary classification model that can accurately determine if a customer is likely to exit based on their demographic and service usage data.

The notebook demonstrates the following core steps:
1.  **Data Acquisition:** Programmatically download the required dataset from Kaggle.
2.  **Data Preprocessing:** Handle categorical variables and scale numerical features.
3.  **ANN Construction:** Define and compile a deep learning model.
4.  **Training & Evaluation:** Train the ANN and visualize its accuracy over epochs.

## ⚙️ Technology Stack and Dependencies

This project relies on standard Python libraries for data science and deep learning:

| Library | Role |
| :--- | :--- |
| **`pandas` & `numpy`** | Data loading, manipulation, and numerical operations. |
| **`scikit-learn`** | Data splitting (`train_test_split`), categorical encoding (`LabelEncoder`, `ColumnTransformer`), and feature scaling (`StandardScaler`). |
| **`tensorflow` / `keras`** | Building, compiling, and training the Artificial Neural Network (ANN) (`Sequential`, `Dense`). |
| **`matplotlib`** | Plotting the training history (accuracy vs. validation accuracy). |

### Installation

```bash
pip install pandas numpy scikit-learn tensorflow matplotlib
```bash
pip install pandas numpy scikit-learn tensorflow matplotlib
