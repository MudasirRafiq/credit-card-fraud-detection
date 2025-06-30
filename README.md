# 💳 Credit Card Fraud Detection

This project uses machine learning to detect fraudulent transactions in a highly imbalanced credit card dataset.

---

## 📌 Objective

To classify transactions as **fraudulent** or **non-fraudulent** using supervised learning algorithms and proper handling of class imbalance.

---

## 🧾 Dataset Overview

- Real-world credit card transactions (anonymized)
- 31 features: V1–V28 (PCA-transformed), Time, Amount, and Class
- Highly imbalanced (fraud = 0.17%)

---

## 🛠️ Tools & Libraries

- Python, Jupyter Notebook  
- Pandas, NumPy  
- Scikit-learn (Logistic Regression, Random Forest, SMOTE)  
- Matplotlib, Seaborn  

---

## ⚙️ Project Workflow

1. **EDA**: Visualized distribution of transaction types  
2. **Preprocessing**:
   - Normalized 'Amount' and 'Time'
   - Handled class imbalance with SMOTE
3. **Modeling**:
   - Evaluated Logistic Regression and Random Forest
   - Used confusion matrix, precision, recall, F1-score
4. **Visualization**:
   - Heatmaps and bar plots for insights

---

## 📈 Results

- Random Forest performed best for fraud detection
- SMOTE significantly improved recall for minority class
- Balanced accuracy and interpretability

---

## 🧠 Learnings

- Real-world fraud detection is about **precision** + **recall**
- Importance of **class imbalance handling**
- Visualization helps understand risk thresholds

---

## 🗂️ Project Files

- `credit_card_fraud.ipynb`: Main notebook  
- `creditcard.csv`: Dataset  

---

## 👤 Author

Mudasir Rafiq  
[GitHub](https://github.com/MudasirRafiq) | [LinkedIn] www.linkedin.com/in/mudasir-rafiq-aa3b72193
