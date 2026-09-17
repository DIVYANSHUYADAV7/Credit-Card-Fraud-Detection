# Credit-Card-Fraud-Detection-Using-Machine-Learning

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning.

The main objective is to identify fraudulent transactions and evaluate different classification models using performance metrics such as Precision, Recall, and F1-Score.

The project also addresses the class imbalance problem using SMOTE (Synthetic Minority Over-sampling Technique).

---

## 📊 Dataset

The dataset contains credit card transaction information.

### Features:
- Time: Time elapsed between transactions
- V1 to V28: PCA-transformed features
- Amount: Transaction amount
- Class: Target variable
  - 0: Genuine transaction
  - 1: Fraudulent transaction

The dataset is highly imbalanced, with fraudulent transactions representing a very small proportion of total transactions.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

---

## 🔍 Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Missing Value Analysis
4. Feature Scaling
5. Class Imbalance Analysis
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. SMOTE-Based Resampling
10. Random Forest Model Training

---

## 🤖 Machine Learning Models

The following models were implemented:

- Decision Tree Classifier
- Random Forest Classifier
- Logistic Regression

Random Forest was selected for further experimentation with resampled data.

---

## ⚖️ Handling Class Imbalance

The dataset contains significantly fewer fraudulent transactions than genuine transactions.

To address this issue, SMOTE (Synthetic Minority Over-sampling Technique) was used to generate synthetic samples for the minority class.

This helps the model learn patterns associated with fraudulent transactions.

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

In fraud detection, Recall and Precision are particularly important for understanding the model's performance.

---

## 🚀 How to Run the Project

### 1. Clone the Repository

git clone YOUR_GITHUB_REPOSITORY_LINK

### 2. Install Dependencies

pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

### 3. Open the Notebook

jupyter notebook

### 4. Run the Project

Open the Credit Card Fraud Detection notebook and execute the cells.

---

## 📁 Project Structure

Credit-Card-Fraud-Detection/
│
├── Credit card.ipynb
├── creditcard.csv
├── model.pkl
└── README.md

---

## 🔮 Future Improvements

- Apply SMOTE only to the training dataset
- Perform hyperparameter tuning
- Implement cross-validation
- Compare ROC-AUC and PR-AUC
- Optimize the classification threshold
- Deploy the model using Streamlit

---

