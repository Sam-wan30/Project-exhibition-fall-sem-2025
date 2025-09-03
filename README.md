# 🔒 Credit Card Fraud Detection

An end-to-end **machine learning project** to detect fraudulent credit card transactions in **real time**.  
Built using **Random Forest Classifier** with **SMOTE** for handling class imbalance.  
The system achieves **87% precision** and **79% recall**, making it highly reliable for financial fraud prevention.

---

## 📌 Features
- ✅ **High Precision (87%)** – minimizes false positives
- ⚡ **Real-Time Detection** – instantly flags suspicious transactions
- 📊 **Handles Imbalanced Data** – uses **SMOTE** to boost recall (79%)
- 🔍 **Feature Engineering** – PCA-based anonymized features (V1–V28)
- 📈 **Robust Evaluation** – AUPRC score of **0.83**

---

## 📊 Dataset
- **Source:** [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Transactions:** 284,807  
- **Fraud Cases:** ~0.17% of total (highly imbalanced)  
- **Features:**  
  - `V1–V28` → PCA-transformed features  
  - `Time` → Seconds elapsed since first transaction  
  - `Amount` → Transaction value  
  - `Class` → 1 = Fraud, 0 = Normal  

---

## ⚙️ Tech Stack
- **Python** – NumPy, Pandas, Scikit-learn  
- **Machine Learning** – Random Forest Classifier, SMOTE  
- **Visualization** – Matplotlib, Seaborn  
- **Frontend Presentation** – HTML, CSS, JavaScript, Bootstrap  

---

## 📈 Results
| Metric     | Score |
|------------|-------|
| Precision  | **87%** |
| Recall     | **79%** |
| AUPRC      | **0.83** |

---

## 🖥️ Landing Page
We designed a **Bootstrap-based website** to present the project with:  
- Hero section & project overview  
- Key features and dataset explanation  
- Results with precision, recall, AUPRC  
- Team details  

---

## 👥 Team – Group 8 (VIT Bhopal University)
- Utkarsh  
- Nikhil  
- Mokshit  
- Samiksha  
- Medha  

---

## 🌟 Future Improvements
- Integration with **real-time payment APIs**  
- Experiment with **Deep Learning models (LSTM, Autoencoders)**  
- Deploy as a **web app with Flask/Django**  
- Live dashboards for fraud monitoring  

---

## 📜 License
This project is for **academic and research purposes only**.  
Not intended for production financial systems.  

---
✨ *“AI-powered real-time credit card fraud detection with Random Forest + SMOTE.”*
