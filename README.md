# 📡 Telecom Customer Churn Prediction

## 📌 Project Overview
This project predicts whether a telecom customer is likely to churn (leave the service) based on their usage patterns, service plans, and customer service interactions.  
The goal is to provide telecom companies with a proactive tool for identifying high-risk customers, enabling targeted retention strategies and reducing revenue loss.

---

## 📊 Dataset

**Sources:**
- `churn-bigml-80.csv` – Training dataset  
- `churn-bigml-20.csv` – Testing dataset  

**Key Features:**
- **Demographics** – State, Area Code, International Plan, Voice Mail Plan  
- **Usage Metrics** – Total day/evening/night charges, call counts, and minutes  
- **Customer Service Interactions** – Number of customer service calls  
- **Target Variable** – Churn (Yes/No)

**Data Preparation:**
- Missing value handling  
- Categorical encoding  
- Feature scaling  
- Train-test split (80% training, 20% testing)

---

## 🎯 Objectives
- Clean and preprocess the telecom customer dataset  
- Identify key patterns and correlations related to churn  
- Build and compare multiple classification models  
- Optimize performance with ensemble techniques  
- Provide business insights for customer retention

---

## 🧠 Models & Techniques
- Logistic Regression  
- Random Forest  
- Gradient Boosting  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- XGBoost  
- **Stacked Ensemble** (Random Forest + Logistic Regression + Gradient Boosting)  
- Model evaluation using **Recall, Precision, F1 Score, Accuracy, and ROC-AUC**  

---

## 📈 Performance Metrics

**Best Model:** Stacked Ensemble  
- Recall: **0.8889**  
- Precision: **0.7207**  
- F1 Score: **0.7960**  
- Accuracy: **0.8633**  
- ROC-AUC: **0.9215**  
- Avg CV Recall: **0.8339**  

Recall was prioritized since missing a churner is costlier than a false positive.

---

## 🔍 Key Findings
- High churn rates among customers with **international plans**  
- Frequent **customer service calls** strongly linked to churn  
- High **day-time charges** increase churn likelihood  
- Ensemble methods outperform individual base learners in recall and stability  

---

## 📊 Visualizations
- Churn distribution bar chart  
- Correlation heatmap  
- Feature importance plot  
- Precision-Recall curve comparison  
- Confusion matrices for top models  

---

## 📂 Folder Structure
telecom-churn-prediction/
├── data/
│   ├── churn-bigml-80.csv
│   ├── churn-bigml-20.csv
├── notebooks/
│   ├── telecom_churn_analysis.ipynb
├── models/
│   ├── stacked_ensemble.pkl
├── outputs/
│   ├── visuals/
│   ├── metrics/
├── README.md


---

## 🔮 Future Enhancements
- Incorporate time-series features such as customer tenure trends  
- Test deep learning models for large-scale datasets  
- Deploy real-time churn prediction system with API integration  
- Build a retention recommendation engine for at-risk customers  

---

## 👤 Author
**Pragathi Porawakara Arachchige**  
📎 [GitHub Profile](https://github.com/PragathiM007)  
Bellevue University – DSC680 Applied Data Science  

---

## 📜 License
This project is licensed under the **PAPM License**.  
