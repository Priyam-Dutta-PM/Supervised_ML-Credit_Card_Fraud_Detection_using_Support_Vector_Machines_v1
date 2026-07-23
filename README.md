# Credit-Card-Fraud-Detection-using-Support-Vector-Machines-v1
Detecting fraudulent credit card transactions using SVM with imbalanced data handling.
# 💳 Credit Card Fraud Detection using Support Vector Machines

A machine learning project that applies **Support Vector Machines (SVM)** to detect fraudulent credit card transactions. The project addresses the challenges of highly imbalanced financial data through preprocessing, feature scaling, and model evaluation using multiple classification metrics.

---

## 📖 Overview

Credit card fraud detection is a critical application of machine learning in the financial sector. Since fraudulent transactions represent only a tiny fraction of all transactions, building an effective classifier requires careful handling of class imbalance and robust evaluation metrics.

This project develops and evaluates SVM-based models for binary classification, comparing their performance in identifying fraudulent transactions while minimizing false positives.

---

## 🎯 Objectives

- Detect fraudulent credit card transactions using Support Vector Machines.
- Address severe class imbalance through preprocessing techniques.
- Train and evaluate SVM classifiers.
- Compare model performance using multiple evaluation metrics.
- Visualize classification performance using ROC curves and confusion matrices.

---

## 📂 Dataset

**Dataset:** Credit Card Fraud Detection Dataset (Kaggle)

### Dataset Characteristics

| Attribute | Value |
|-----------|-------|
| Transactions | 284,807 |
| Fraud Cases | 492 |
| Features | 30 |
| Target | Fraud / Legitimate |
| Problem Type | Binary Classification |

The dataset contains anonymized transaction features obtained using PCA, along with transaction amount, transaction time, and the class label.

---

## 🛠️ Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 🔄 Project Workflow

```
Data Loading
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Class Distribution Analysis
      │
      ▼
Feature Scaling
      │
      ▼
Handling Class Imbalance
      │
      ▼
Train-Test Split
      │
      ▼
Support Vector Machine Training
      │
      ▼
Model Evaluation
      │
      ▼
Performance Comparison
```

---

## 📊 Evaluation Metrics

The trained models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC Score
- Confusion Matrix
- Classification Report
- ROC Curve
- Performance Comparison Charts

---
**Performance Analysis**

>The performance of the models is evaluated using metrics including accuracy, precision, recall, F1-score, ROC-AUC, confusion matrices, ROC curves, and training time. By comparing the strengths and limitations of Linear and RBF SVMs, this study aims to identify the most suitable classifier for credit card fraud detection while highlighting the practical trade-offs between maximizing fraud detection and minimizing false positive predictions.

>Credit card fraud detection is a challenging binary classification problem due to the highly imbalanced nature of transaction data. This project compares the performance of Linear and Radial Basis Function (RBF) Support Vector Machine (SVM) classifiers for identifying fraudulent transactions.

>After balancing the dataset and applying feature scaling, both models are trained and evaluated using metrics such as accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrices. The comparison highlights the effectiveness of linear and non-linear SVMs in detecting fraudulent credit card transactions.


## 📈 Results


> **Two Support Vector Machine (SVM) classifiers, namely the Radial Basis Function (RBF) SVM and Linear SVM, were trained and evaluated on a balanced subset of the Credit Card Fraud Detection dataset**.

> Both models achieved an overall accuracy of 96% and an F1-score of 0.90, demonstrating strong classification performance. The RBF SVM achieved a higher precision of 96%, indicating fewer false positive fraud detections, while the Linear SVM achieved a higher recall of 90%, successfully identifying a greater proportion of fraudulent transactions compared to the RBF SVM (84% recall).

> Both models exhibited comparable overall performance, as reflected by their identical F1-scores, with the trade-off lying between precision and recall. Since fraud detection applications generally prioritize minimizing missed fraudulent transactions, the Linear SVM provides a slight practical advantage by detecting more fraud cases, whereas the RBF SVM is better suited for scenarios where reducing false alarms is more critical.

>Overall, the results demonstrate that both linear and non-linear SVMs are effective classifiers for credit card fraud detection when trained on a balanced dataset, with the choice of model depending on the desired balance between fraud detection sensitivity and false positive rates.


The project includes comprehensive performance analysis through:

- ✅ Confusion Matrix
- ✅ ROC Curve
- ✅ Classification Report
- ✅ Accuracy, Precision, Recall & F1-score Comparison
- ✅ ROC-AUC Comparison
- ✅ Training Time Analysis
- ✅ Model Performance Visualizations

| Model | Accuracy | Precision | Recall | F1-score |
|--------|---------:|----------:|--------:|---------:|
| Support Vector Machine | 99.94% | 93.12% | 88.57% | 90.79% |



---

## 📁 Repository Structure

```
credit-card-fraud-detection-svm/
│
├── Credit_Card_Fraud_Detection_SVM.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

- Compare with Random Forest and XGBoost
- Apply SMOTE for oversampling
- Hyperparameter optimization using GridSearchCV
- Explore anomaly detection methods
- Deploy the trained model as a web application

---

## 💼 Skills Demonstrated

- Machine Learning
- Binary Classification
- Support Vector Machines
- Financial Fraud Detection
- Imbalanced Data Handling
- Feature Engineering
- Model Evaluation
- Data Visualization

---

## 📚 References

- Credit Card Fraud Detection Dataset (Kaggle)
- Scikit-learn Documentation
- TensorFlow & Python Documentation

---

## 👤 Author

**P D**

Machine Learning | Data Science | Artificial Intelligence
