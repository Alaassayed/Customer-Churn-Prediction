<div align="center">

# 🚀 Customer Churn Prediction using Machine Learning

### End-to-End Machine Learning Project

<img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" width="700">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=for-the-badge&logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikit-learn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=for-the-badge&logo=github)

</div>

---

# 📑 Table of Contents

- Project Overview
- Dataset
- Features
- Machine Learning Workflow
- Models Used
- Evaluation Metrics
- Hyperparameter Tuning
- Results
- Project Screenshots
- Technologies
- Installation
- Project Structure
- Future Improvements

---

# 📌 Project Overview

This project predicts whether a customer is likely to leave a telecommunications company using Machine Learning techniques.

The project includes the complete Machine Learning pipeline from data preprocessing to model evaluation and hyperparameter tuning.

---

# 📊 Dataset

**Dataset:** IBM Telco Customer Churn Dataset

**Target Variable:** Churn

**Problem Type:** Binary Classification

---

# 📈 Features

Some important features used:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Internet Service
- Contract
- Payment Method
- Monthly Charges
- Total Charges

---

# ⚙ Machine Learning Workflow

- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Label Encoding
- One-Hot Encoding
- Feature Scaling
- Train/Test Split
- Model Training
- Hyperparameter Tuning
- Model Evaluation

---

# 🤖 Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

---

# 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report
- ROC Curve

---

# 🔧 Hyperparameter Tuning

GridSearchCV was used to optimize the Random Forest model by tuning:

- Number of Trees
- Maximum Depth
- Minimum Samples Split
- Minimum Samples Leaf

---

# 🏆 Results

After comparing multiple Machine Learning algorithms, the Random Forest model achieved the best performance after hyperparameter tuning.

---

# 🖼️ Project Screenshots

## Customer Churn Distribution

<p align="center">
  <img src="https://github.com/user-attachments/assets/f771410d-1557-4885-a4c6-f1cd750e598f" width="700"/>
</p>
---

## Contract vs Churn

<p align="center">
  <img src="https://github.com/user-attachments/assets/2c1b9329-5042-47f0-a3b3-874bd836500c" width="700"/>
</p>

---

## Correlation Heatmap

<p align="center">
  <img src=""images/heatmap.png" width="700"/>
</p>

---

## ROC Curve

<p align="center">
  <img src="https://github.com/user-attachments/assets/77be9986-f10d-410b-a268-27af48423a40" width="700"/>
</p>



---

## Feature Importance

<p align="center">
  <img src="https://github.com/user-attachments/assets/43ea4d5b-43fb-452a-9eb0-375de7202edb" width="700"/>
</p>

---

## SHAP Summary Plot

<p align="center">
  <img src="https://github.com/user-attachments/assets/7a3b04e5-ef89-4a27-8ac2-9d9e5e5dce89" width="700"/>
</p>

---

# 💻 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- SHAP
- Joblib
- Google Colab

---

# 📂 Project Structure

```
Customer-Churn-Prediction/
│
├── churn_prediction.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── README.md
├── requirements.txt
├── .gitignore
│
├── images/
│   ├── churn_distribution.png
│   ├── contract_vs_churn.png
│   ├── heatmap.png
│   ├── roc_curve.png
│   ├── feature_importance.png
│   └── shap_summary.png
│
└── models/
    └── random_forest.pkl
```

---

# ⚡ Installation

```bash
git clone https://github.com/YOUR_USERNAME/Customer-Churn-Prediction.git
```

```bash
cd Customer-Churn-Prediction
```

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

Open the notebook:

```
churn_prediction.ipynb
```

Run all cells sequentially.



# 👩‍💻 Author

**alaa**

Machine Learning & Data Science Enthusiast

GitHub:Alaassayed



---

<div align="center">

⭐ If you found this project useful, please consider giving it a star!

</div>
