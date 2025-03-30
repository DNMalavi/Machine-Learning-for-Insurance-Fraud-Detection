# 🕵️‍♂️ Insurance Fraud Detection with Machine Learning

This project explores how machine learning can be applied to detect fraudulent insurance claims using structured data. It includes supervised, unsupervised, and cost-sensitive learning strategies to maximize fraud recall and minimize false positives in a highly imbalanced dataset.

---

## 📊 Objective

To develop a robust fraud detection system that accurately flags high-risk insurance claims by:
- Training multiple supervised models
- Applying SMOTE and cost-sensitive learning
- Using explainable AI (SHAP) for model interpretation
- Exploring unsupervised techniques for anomaly detection and segmentation

---

## 🧠 Models Used

### Supervised Learning:
- Logistic Regression (with SMOTE & class weights)
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest (RF)
- XGBoost (with SHAP analysis)
- Multi-Layer Perceptron (MLP)
- Stacked Ensemble
- PLS-DA

### Unsupervised Learning:
- Isolation Forest
- K-Means Clustering (post PCA and t-SNE)
- Mutual Information for feature relevance

---

## 📌 Key Features

- **Recall-Focused Strategy**: Logistic Regression (SMOTE) and SVM (cost-sensitive) achieved highest fraud recall (52% and 47% respectively).
- **Explainable AI**: SHAP analysis highlighted `Claim_Amount`, `Customer_Income`, and `Claim_Submission_Delay` as top predictors.
- **Anomaly Detection**: Isolation Forest successfully profiled outliers, while K-Means revealed behavioral claim clusters.
- **Feature Selection**: Used mutual information to isolate impactful features and reduce noise.
- **Model Evaluation**: Precision, recall, F1-score, ROC-AUC, and PR-AUC were used to assess model performance.

---

## 🧰 Tech Stack

- **Language**: Python
- **Libraries**: `scikit-learn`, `xgboost`, `shap`, `imbalanced-learn`, `matplotlib`, `seaborn`, `pandas`, `numpy`
- **Tools**: Jupyter Notebook, VS Code, Git

---


## 🚀 Business Impact

This project demonstrates how AI can:
- Increase detection of high-risk insurance claims
- Support fraud investigation teams with intelligent flagging
- Reduce financial loss while minimizing disruption to legitimate customers

---

## 📌 Next Steps

- Fine-tune decision thresholds
- Integrate model into a Flask API for deployment
- Extend anomaly detection with autoencoders or one-class SVM
- Build a dashboard for claim reviewers

---

## 👤 Author

**Derick Malavi**  
📫 [LinkedIn](https://www.linkedin.com/in/derick-malavi-64742643/) | 🌍 [Portfolio](https://www.datascienceportfol.io/malaviderick)

---

## 📝 License

This project is open-source and available under the MIT License.


