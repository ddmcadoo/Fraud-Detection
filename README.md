# Fraud-Detection# 🕵️‍♀️ Fraud Detection Using Machine Learning

This project uses machine learning techniques to detect fraudulent transactions based on a publicly available dataset from Kaggle. The goal is to build and evaluate models that can effectively distinguish between legitimate and fraudulent credit card transactions.

## 📊 Dataset

The dataset used in this project is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle. It contains transactions made by European cardholders in September 2013, with features transformed using PCA to protect confidentiality.

- **Total transactions:** 284,807  
- **Fraudulent transactions:** 492  
- **Features:** 30 (including `Time`, `Amount`, and anonymized `V1`–`V28`)  
- **Target:** `Class` (1 = fraud, 0 = legitimate)

## 🛠️ Project Workflow

1. **Data Preprocessing**
   - Handling class imbalance
   - Scaling numeric features
   - Splitting train/test sets

2. **Feature Engineering**
   - Exploratory data analysis (EDA)
   - Correlation analysis
   - Feature selection

3. **Model Selection**
   - Logistic Regression  
   - Random Forest  
   - XGBoost  
   - Neural Network  

4. **Evaluation**
   - Accuracy  
   - Precision  
   - Recall  
   - F1-score  
   - ROC-AUC  

## 🧪 How to Run

This project is implemented in a Jupyter Notebook. To run it:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/fraud-detection.git
   cd fraud-detection
