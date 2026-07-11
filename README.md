# 💳 Loan Default Prediction

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-green)
![LightGBM](https://img.shields.io/badge/LightGBM-Gradient%20Boosting-success)
![License](https://img.shields.io/badge/License-Educational-blue)

</p>

A complete **Machine Learning project** that predicts whether a borrower is likely to default on a loan using multiple classification algorithms. The project demonstrates an end-to-end ML workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, risk segmentation, and business insights.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Dataset](#-dataset)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Workflow](#-workflow)
- [How to Run](#-how-to-run)
- [Example Outputs](#-example-outputs)
- [Applications](#-applications)
- [Future Improvements](#-future-improvements)
- [Author](#-author)
- [License](#-license)

---

# 📖 Overview

Loan default prediction is one of the most important applications of Machine Learning in the banking and finance industry. Financial institutions use predictive models to estimate the probability that a borrower will fail to repay a loan.

This project develops a complete machine learning pipeline to identify high-risk borrowers, helping financial institutions:

- Reduce credit losses
- Improve loan approval decisions
- Optimize lending strategies
- Perform portfolio risk analysis
- Support risk-based pricing

---

# 📂 Dataset

The project uses the **Loan Default Prediction** dataset available on Kaggle.

**📥 Dataset Link**

https://www.kaggle.com/code/aditigarg23199/loandefaultprediction-5baselinemodel-riskanalytics/input?select=loan.csv

Download the **`loan.csv`** dataset and place it inside the project directory before running the notebook.

---

# ✨ Features

- 📥 Data Loading & Cleaning
- 📊 Exploratory Data Analysis (EDA)
- 🔧 Feature Engineering
- ⚙️ Data Preprocessing
- 🤖 Multiple Machine Learning Models
- 📈 Model Evaluation & Comparison
- 🚦 Risk Bucketing
- 👥 Customer Segmentation
- 💰 Portfolio Analysis
- 📉 Expected Loss Estimation
- 💡 Business Recommendations

---

# 📁 Project Structure

```text
Loan-Default-Prediction/
│
├── LoanDefaultPrediction.ipynb    # Main Jupyter Notebook
├── loan.csv                       # Dataset (Download from Kaggle)
├── requirements.txt               # Project dependencies
└── README.md                      # Project documentation
```

---

# 🛠️ Tech Stack

## Programming Language

- 🐍 **Python 3.x**
  https://www.python.org/

## Libraries & Tools

| Tool | Purpose |
|------|---------|
| **NumPy** | Numerical Computing |
| https://numpy.org/ | |
| **Pandas** | Data Manipulation |
| https://pandas.pydata.org/ | |
| **Matplotlib** | Data Visualization |
| https://matplotlib.org/ | |
| **Seaborn** | Statistical Visualization |
| https://seaborn.pydata.org/ | |
| **Scikit-Learn** | Machine Learning Algorithms |
| https://scikit-learn.org/ | |
| **XGBoost** | Gradient Boosting |
| https://xgboost.readthedocs.io/ | |
| **LightGBM** | Gradient Boosting Framework |
| https://lightgbm.readthedocs.io/ | |
| **Joblib** | Model Serialization |
| https://joblib.readthedocs.io/ | |
| **Jupyter Notebook** | Interactive Development |
| https://jupyter.org/ | |

---

# 🔄 Workflow

## 1️⃣ Environment Setup

- Import libraries
- Configure plotting options
- Create output directories

---

## 2️⃣ Data Loading

- Load dataset
- Inspect dataset
- Check missing values
- Analyze target variable

---

## 3️⃣ Data Preprocessing

- Handle missing values
- Encode categorical variables
- Feature scaling
- Train-Test Split

---

## 4️⃣ Exploratory Data Analysis (EDA)

- Univariate Analysis
- Bivariate Analysis
- Correlation Analysis
- Distribution Analysis
- Target Variable Analysis
- Data Visualization

---

## 5️⃣ Feature Engineering

- Create derived features
- Select informative variables
- Prepare model-ready dataset

---

## 6️⃣ Model Training

The notebook evaluates multiple machine learning models:

- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost
- LightGBM

---

## 7️⃣ Model Evaluation

Performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 8️⃣ Risk Bucketing

Predicted probabilities are converted into:

- 🟢 Low Risk
- 🟡 Medium Risk
- 🔴 High Risk

These categories help transform predictions into actionable business decisions.

---

## 9️⃣ Portfolio Analysis

The notebook also includes:

- Portfolio Segmentation
- Default Rate Analysis
- Risk Distribution
- Expected Loss Estimation

---

## 🔟 Business Insights

The project concludes with recommendations for:

- Loan Approval Strategy
- Credit Risk Management
- Portfolio Optimization
- Risk-Based Pricing

---

# 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/ajinkya029/Loan-Default-Prediction.git
```

```bash
cd Loan-Default-Prediction
```

---

### 2. Download the Dataset

Download **loan.csv** from the Kaggle dataset link and place it inside the project folder.

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Launch the Notebook

```bash
jupyter notebook LoanDefaultPrediction.ipynb
```

---

# 📊 Example Outputs

The notebook generates several visualizations and analytical outputs, including:

- 📈 Distribution Plots
- 🔥 Correlation Heatmap
- 📊 Feature Importance
- 📉 ROC Curve
- ✅ Confusion Matrix
- 🚦 Risk Bucket Distribution
- 👥 Customer Segmentation
- 💰 Portfolio Analysis
- 📉 Expected Loss Analysis

---

# 💼 Applications

This project can be applied in:

- Credit Risk Assessment
- Loan Approval Automation
- Banking Analytics
- Financial Risk Management
- FinTech Solutions
- Lending Decision Support Systems

---

# 🚀 Future Improvements

- Hyperparameter Optimization
- SHAP Explainability
- Cross Validation Pipeline
- Flask/FastAPI Deployment
- Streamlit Dashboard
- Real-Time Prediction API
- Model Monitoring
- Data Drift Detection

---

# 👨‍💻 Author

**Ajinkya**

An end-to-end Machine Learning project demonstrating practical applications of:

- Machine Learning
- Credit Risk Modeling
- Banking Analytics
- Financial Risk Analysis
- Business Intelligence

---

# 📜 License

This project is intended for **educational and research purposes**.

Feel free to modify, improve, and use it for your own learning and projects.

⭐ If you found this project useful, consider giving it a **star** on GitHub!
