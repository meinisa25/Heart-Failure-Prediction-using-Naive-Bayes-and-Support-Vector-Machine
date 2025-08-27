# **Heart Failure Prediction using Naive Bayes and Support Vector Machine**

---

## 📱 **About the Project**

Cardiovascular disease (CVD) is the leading cause of death worldwide, with heart failure being one of the most common outcomes. The dataset used in this project contains **13 clinical features** such as age, anemia, diabetes, high blood pressure, ejection fraction, and more, to predict the mortality risk of patients (**DEATH_EVENT**).  

This project aims to:  
1. Implement **Naive Bayes** and **Support Vector Machine (SVM)** classifiers on a heart failure dataset.  
2. Compare the performance of both models in classifying high-risk patients. 
3. Evaluate the models using metrics such as accuracy, precision, recall, confusion matrix, and ROC/AUC curve.  

---

## 📋 **Dataset**

- **Source**: Heart Failure Prediction Dataset [https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data].  
- **Main Features**:  
  - Age, anemia, diabetes, high blood pressure.  
  - Ejection fraction, serum creatinine, serum sodium, etc.  
- **Target**:  
  - `DEATH_EVENT` (1 = death, 0 = survival).  
- **Dataset Size**:  
  - 299 samples, 13 predictor features.  

---

## 📂 **Methodology**

**1. Data Preprocessing**  
- Handle numerical & categorical variables.  
- Feature scaling and encoding.  
- Train-test split for evaluation.  

**2. Model Building**  
- **Naive Bayes Classifier**: simple & fast, suitable for small datasets.  
- **Support Vector Machine (SVM)**: constructs hyperplanes for classification.  

**3. Evaluation Metrics**  
- Accuracy, Precision, Recall, F1-score.  
- Confusion Matrix.  
- Precision-Recall Curve.  
- ROC Curve & AUC.  

---

## 🖥 **Programming Language & Libraries**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)  
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white)  
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)  
![Scikit-learn](https://img.shields.io/badge/-ScikitLearn-F7931E?style=flat&logo=scikit-learn&logoColor=white)  
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat&logo=python&logoColor=white)  
![Seaborn](https://img.shields.io/badge/-Seaborn-4EAEBC?style=flat&logo=python&logoColor=white)  

---

## 📈 **Model Results**

**1. Naive Bayes**  
- Accuracy: **76%**  
- Offers simplicity, efficiency, and robust performance on medical datasets.

**2. Support Vector Machine (SVM)**  
- Accuracy: **73%**  
- Achieves competitive accuracy with strong generalization, especially when kernel functions are applied.   

**Evaluation Highlights**:    
- Machine learning can effectively support **early detection of heart failure risk**, enabling timely interventions.  
- Both Naive Bayes and SVM show reliable results, making them promising tools for **healthcare decision support systems**.  
- This study demonstrates how combining clinical expertise with AI can contribute to **better patient outcomes**.  

**Conclusion**:  
This project emphasizes the role of machine learning in healthcare analytics. 
By applying Naive Bayes and Support Vector Machine to heart failure data, we show how AI models can help **predict patient survival** and support medical practitioners in making informed decisions.  
Further improvements are needed, such as data balancing techniques, hyperparameter tuning, or ensemble methods.  
