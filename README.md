# 🧠 Customer Churn Prediction Model

## 🎯 Project Overview
This project focuses on predicting **customer churn** in a telecommunications dataset using advanced **machine learning** models.  
The objective is to identify **at-risk customers** so that the company can take proactive actions (e.g., loyalty offers, personalized engagement) to improve retention and reduce revenue loss.

---

## 🧩 Business Understanding
Customer churn is one of the major challenges in subscription-based businesses.  
By analyzing behavioral and demographic patterns, this project builds a predictive system capable of flagging customers likely to leave, helping the company **retain high-value clients**.

---

## ⚙️ Methodology
The project follows the **CRISP-DM** (Cross-Industry Standard Process for Data Mining) framework:

1. **Business Understanding** – Define the problem and objectives.  
2. **Data Understanding** – Explore dataset structure and imbalance.  
3. **Data Preparation** – Handle missing values, encode categorical features, and scale numerical variables.  
4. **Modeling** – Train several classifiers (Logistic Regression, SVM, Random Forest, LightGBM).  
5. **Evaluation** – Compare performance using multiple metrics.  
6. **Deployment Insight** – Identify key features driving churn.

---

## 📊 Data Preparation
- **Feature Engineering:** Created new features (e.g., tenure groups, contract type indicators).  
- **Encoding:** One-Hot and Label Encoding for categorical variables.  
- **Normalization:** StandardScaler for numerical features.  
- **Imbalance Handling:** SMOTE (Synthetic Minority Over-sampling Technique).  

---

## 🤖 Models Used
| Model | Description | Key Features |
|--------|--------------|--------------|
| **Logistic Regression** | Baseline interpretable classifier | Fast, good interpretability |
| **SVM (Support Vector Machine)** | Finds optimal decision boundary | Works well in high dimensions |
| **Random Forest** | Ensemble of decision trees | Handles non-linear relations |
| **LightGBM** | Gradient boosting on trees | High accuracy, fast training |

---

## 📈 Model Evaluation
Evaluation metrics used:
- **ROC-AUC Score**
- **Precision-Recall Curve**
- **Confusion Matrix**
- **F1-Score**
- **Accuracy and Recall**

✅ **Best performing model:** LightGBM, achieving the highest ROC-AUC and balanced precision/recall.

---

## 💡 Key Insights
- Contract type and tenure length are the strongest churn indicators.  
- Customers with **month-to-month contracts**, **low tenure**, and **no tech support** are most likely to churn.  
- Reducing churn among high-risk customers could significantly improve overall revenue retention.

---

## 🧰 Technologies & Tools
- **Language:** Python  
- **Libraries:** pandas, NumPy, scikit-learn, LightGBM, imbalanced-learn, matplotlib, seaborn  
- **Framework:** Jupyter Notebook  
- **Version Control:** Git & GitHub

---

