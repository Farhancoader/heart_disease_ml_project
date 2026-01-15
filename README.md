# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Overview
Heart disease is one of the leading causes of death worldwide.  
This project aims to **predict the presence of heart disease** using supervised machine learning techniques based on clinical and demographic features.

The project demonstrates a **complete end-to-end machine learning workflow**, from data preprocessing to model evaluation and interpretation.

---

## 🎯 Objectives
- Build reliable ML models to predict heart disease
- Compare multiple algorithms fairly
- Optimize models using hyperparameter tuning
- Evaluate models using advanced metrics beyond accuracy
- Interpret model predictions using feature importance

---

## 🧠 Models Used
The following machine learning models were implemented and compared:

- **K-Nearest Neighbors (KNN)**
- **Logistic Regression**
- **Random Forest Classifier**

Hyperparameters were optimized using **RandomizedSearchCV**.

---

## 🔄 Machine Learning Pipeline
1. Data loading and inspection  
2. Train–test split  
3. Feature scaling using `StandardScaler`  
4. Model training with hyperparameter tuning  
5. Model evaluation on unseen test data  
6. Model interpretation and conclusions  

---

## 📊 Evaluation Metrics
To ensure robust evaluation, multiple metrics were used:

- **Accuracy**
- **Confusion Matrix**
- **Precision, Recall, F1-Score**
- **ROC Curve**
- **ROC-AUC Score**

Accuracy alone can be misleading in medical datasets, so ROC-AUC and recall were emphasized.

---

## 📈 Results Summary
- All models achieved competitive performance
- **Random Forest** showed strong overall performance and stability
- ROC-AUC confirmed good class separation
- Feature importance improved interpretability and trust in predictions

---

## 🌲 Feature Importance
Random Forest feature importance was used to identify the most influential features contributing to heart disease prediction.  
This helps in understanding **which clinical factors matter most**.

---

## 🛠️ Technologies & Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure
