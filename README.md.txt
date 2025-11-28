# Credit Default Prediction — Machine Learning Project (ESILV 2025)

> ⚠️ **Note:** This version is functional but not final. Several improvements (feature engineering, hyperparameter tuning, SHAP explainability) will be added later.

## 📌 Project Description
This project aims to predict whether a client will default on a loan using the **Home Credit Default Risk** dataset from Kaggle.  
The notebook includes data preprocessing, handling missing values, model selection, class imbalance strategies, ensemble methods, and evaluation metrics.

## 📚 Course Alignment (ESILV Machine Learning — N. Mellouli)
This project follows the concepts studied in:
- **Lesson 1:** Data Preprocessing  
- **Lesson 3:** Imbalanced Learning  
- **Lesson 5:** Decision Trees  
- **Lesson 6:** Ensemble Learning & Grid Search  

## 🗂 Project Structure
credit default ml/
├── notebooks/
│ └── notebook.ipynb
├── data/ # CSV not included (ignored)
├── models/
├── src/
├── .gitignore
└── README.md


## 🚀 Best Model (Step 3 Results)
- **XGBoost (tuned)**  
  - AUC ≈ 0.762  
  - F1 ≈ 0.313 (tuned threshold)
  - Recall ≈ 0.43  

## 📥 Dataset
Data must be downloaded manually from Kaggle:  
https://www.kaggle.com/competitions/home-credit-default-risk/data  
Place `application_train.csv` in **/data/**.

