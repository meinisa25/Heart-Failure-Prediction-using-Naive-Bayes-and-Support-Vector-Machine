# Heart-Failure-Prediction-using-Naive-Bayes-and-Support-Vector-Machine
This project implements machine learning models to predict mortality risk in patients with heart failure using clinical data. The dataset contains 13 medical features such as age, anemia, diabetes, high blood pressure, and ejection fraction.
🔍 Project Objectives

Apply Naive Bayes and Support Vector Machine (SVM) classifiers.

Compare model performance in predicting death events caused by heart failure.

Highlight challenges of class imbalance in healthcare datasets.

📊 Results

Naive Bayes: 76% accuracy, but low sensitivity for positive class (DEATH_EVENT = 1).

SVM: 73% accuracy, but poor detection of minority class (precision and recall near 0 for DEATH_EVENT = 1).

Evaluation metrics: Confusion Matrix, Precision-Recall Curve, ROC/AUC Curve.

⚙️ Tech Stack

Python

Scikit-learn

Pandas, NumPy

Matplotlib, Seaborn

🚀 Insights

Both models showed reasonable performance on majority class predictions but struggled with minority class detection due to imbalanced data. Future improvements may include data resampling techniques (SMOTE, undersampling/oversampling), hyperparameter tuning, or ensemble methods to enhance prediction of high-risk patients.
