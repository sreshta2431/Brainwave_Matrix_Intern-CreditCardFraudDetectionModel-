# Brainwave_Matrix_Intern-CreditCardFraudDetectionModel

## 🧠 Project Title
**Credit Card Fraud Detection using Machine Learning**

## 📌 Description
This project is part of the Brainwave Matrix Internship and aims to build a machine learning model to detect fraudulent credit card transactions. Fraud detection is a critical application in the financial domain, especially due to the highly imbalanced nature of such datasets.

The model uses standard machine learning techniques along with SMOTE (Synthetic Minority Over-sampling Technique) to handle class imbalance and improve the detection of rare fraudulent activities.

## 📁 Dataset
The dataset used is publicly available on [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).  
- Total transactions: 284,807  
- Fraudulent transactions: 492  
- Features: 30 (anonymized + `Amount`, `Time`)

## ⚙️ Techniques Used
- Logistic Regression
- SMOTE for class imbalance
- Feature scaling (StandardScaler)
- Model evaluation with confusion matrix, classification report, and ROC AUC Score

## 📊 Libraries
- pandas, numpy
- scikit-learn
- imbalanced-learn
- matplotlib, seaborn

## 🚀 How to Run
1. Download the dataset from Kaggle and place `creditcard.csv` in the project folder.
2. Run the `fraud_detection.py` file (or Jupyter Notebook).
3. Results will include performance metrics and a confusion matrix visualization.

## 📈 Outputs
- Classification Report: Precision, Recall, F1-Score
- ROC AUC Score
- Confusion Matrix Heatmap

## 🤖 Future Improvements
- Test with advanced models like Random Forest, XGBoost, or Neural Networks
- Deploy the model with Streamlit or Flask
- Use full dataset with GPU support for better results
