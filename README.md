[![Customer Churn Prediction](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=00E5FF&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=100&lines=Customer+Churn+Prediction;Machine+Learning+%2B+3D+Visualization;End-to-End+ML+Project+2026)](https://git.io/typing-svg)  
[![Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/) [![Scikit--Learn-1.3%2B-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white](https://img.shields.io/badge/Scikit--Learn-1.3%2B-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/) [![Pandas-2.0%2B-150458?style=for-the-badge&logo=pandas&logoColor=white](https://img.shields.io/badge/Pandas-2.0%2B-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/) [![NumPy-1.24%2B-013243?style=for-the-badge&logo=numpy&logoColor=white](https://img.shields.io/badge/NumPy-1.24%2B-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/) [![Matplotlib-3.7%2B-FF6F00?style=for-the-badge&logo=plotly&logoColor=white](https://img.shields.io/badge/Matplotlib-3.7%2B-FF6F00?style=for-the-badge&logo=plotly&logoColor=white)](https://matplotlib.org/) [![Seaborn-0.12%2B-Fcdc00?style=for-the-badge&logo=seaborn&logoColor=white](https://img.shields.io/badge/Seaborn-0.12%2B-Fcdc00?style=for-the-badge&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)  
[![GitHub stars](https://img.shields.io/github/stars/basitali08/customer-churn-prediction?style=social)](https://github.com/basitali08/customer-churn-prediction) [![GitHub forks](https://img.shields.io/github/forks/basitali08/customer-churn-prediction?style=social)](https://github.com/basitali08/customer-churn-prediction)

---

## 📋 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Pipeline](#project-pipeline)
- [Model Performance](#model-performance)
- [Key Findings](#key-findings)
- [Visualizations](#visualizations)
- [Quick Start](#quick-start)
- [Project Structure](#project-structure)
- [Tech Stack](#tech-stack)
- [Author](#author)

---

## 🔍 Overview

> **Predict customer churn in telecom companies with 86% accuracy using Machine Learning — enabling proactive retention strategies.**

Customer churn is the **#1 revenue killer** for telecom companies. This project builds a complete ML system that:

- Analyzes **5,000+ customer records** to detect churn patterns
- Compares **Logistic Regression, Random Forest & Gradient Boosting**
- Identifies **key churn drivers** for targeted retention campaigns
- Achieves **86% accuracy** with the best model
- Provides **actionable business insights** for customer retention

[![Accuracy](https://img.shields.io/badge/Accuracy-86%25-success?style=flat-square&labelColor=1a1a2e&color=00e676)](https://github.com/basitali08/customer-churn-prediction)
[![Precision](https://img.shields.io/badge/Precision-75%25-success?style=flat-square&labelColor=1a1a2e&color=00e676)](https://github.com/basitali08/customer-churn-prediction)
[![Recall](https://img.shields.io/badge/Recall-62%25-success?style=flat-square&labelColor=1a1a2e&color=00e676)](https://github.com/basitali08/customer-churn-prediction)
[![F1-Score](https://img.shields.io/badge/F1--Score-68%25-success?style=flat-square&labelColor=1a1a2e&color=00e676)](https://github.com/basitali08/customer-churn-prediction)
[![Dataset](https://img.shields.io/badge/Dataset-5%2C000_records-blue?style=flat-square&labelColor=1a1a2e&color=0066ff)](https://github.com/basitali08/customer-churn-prediction)

---

## 📊 Dataset

**Source:** Telecom Customer Churn Dataset (Kaggle)

| Feature | Type | Description |
|---------|------|-------------|
| `gender` | Categorical | Male / Female |
| `SeniorCitizen` | Binary | 0 = No, 1 = Yes |
| `Partner` | Categorical | Yes / No |
| `Dependents` | Categorical | Yes / No |
| `tenure` | Numeric | 1 – 72 months |
| `PhoneService` | Categorical | Yes / No |
| `InternetService` | Categorical | DSL, Fiber optic, No |
| `Contract` | Categorical | Month-to-month, One year, Two year |
| `PaymentMethod` | Categorical | Electronic check, Mailed check, Bank transfer, Credit card |
| `MonthlyCharges` | Numeric | $18.25 – $118.75 |
| `TotalCharges` | Numeric | $18.85 – $8684.80 |
| `Churn` | **Target** | **Yes** = Churned, **No** = Retained |

> **Challenge:** ~27% churn rate — moderately imbalanced dataset requiring careful model selection.

---

## 🔄 Project Pipeline

```
📥 Load Data → 🔍 EDA Viz → 🧹 Preprocess → ⚖️ Encode & Scale → 🤖 Train 3 Models → 📊 Evaluate → 💾 Save Model
```

**Step-by-step:**

1. **Data Loading** — Load CSV with 5000+ customer records
2. **EDA** — Visualize churn distribution, correlations, feature relationships
3. **Preprocessing** — Handle missing values, encode categories, scale features
4. **Feature Engineering** — Create meaningful features from raw data
5. **Model Training** — Train Logistic Regression, Random Forest, Gradient Boosting
6. **Evaluation** — Compare accuracy, precision, recall, F1, ROC AUC
7. **Deployment** — Save best model for production use

---

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|----------|-----------|--------|----------|---------|
| Logistic Regression | 82% | 68% | 55% | 61% | 0.78 |
| Random Forest | 84% | 72% | 58% | 64% | 0.81 |
| **Gradient Boosting** | **86%** | **75%** | **62%** | **68%** | **0.84** |

> **Gradient Boosting** was chosen as the best model because it achieves the highest **accuracy (86%)** and **ROC-AUC (0.84)** while maintaining good precision-recall balance.

---

## 🔎 Key Findings

| Indicator | Finding |
|-----------|---------|
| **Contract Type** | Month-to-month contracts have 3x higher churn rate |
| **Tenure** | Customers with <12 months tenure are 2x more likely to churn |
| **Internet Service** | Fiber optic users show 40% higher churn |
| **Payment Method** | Electronic check users churn 25% more than others |
| **Monthly Charges** | Higher charges correlate with increased churn |

---

## 📊 Visualizations

The notebook includes comprehensive visualizations:

- **Churn Distribution** — Pie chart and bar plot
- **Feature Relationships** — Churn by contract, internet service, payment method
- **Tenure Analysis** — Distribution by churn status
- **Correlation Heatmap** — Feature correlations
- **ROC Curves** — Model comparison
- **Feature Importance** — Top predictive features
- **Confusion Matrix** — Best model performance

---

## 🚀 Quick Start

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

### 1. Run the Notebook

Open `customer_churn_prediction.ipynb` in Jupyter Lab / VS Code for the complete step-by-step analysis with visualizations.

### 2. Train the Model

```python
# The notebook will automatically:
# - Load and explore the data
# - Preprocess and encode features
# - Train 3 different models
# - Evaluate and compare performance
# - Save the best model
```

### 3. Use the Saved Model

```python
import joblib

# Load the saved model
model = joblib.load('models/best_churn_model.pkl')
scaler = joblib.load('models/scaler.pkl')

# Make predictions
predictions = model.predict(scaled_features)
```

---

## 📁 Project Structure

```
customer-churn-prediction/
├── customer_churn_prediction.ipynb   # Jupyter notebook (full analysis)
├── requirements.txt                  # Python dependencies
├── models/
│   ├── best_churn_model.pkl         # Trained Gradient Boosting model
│   └── scaler.pkl                   # StandardScaler
└── README.md
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python 3.10+ | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Basic plotting |
| Seaborn | Statistical visualization |
| Scikit-learn | ML models & preprocessing |
| Joblib | Model serialization |

---

**Built with Python, Scikit-learn, Pandas & Seaborn**

[![GitHub stars](https://img.shields.io/github/stars/basitali08/customer-churn-prediction?style=social)](https://github.com/basitali08/customer-churn-prediction) [![GitHub forks](https://img.shields.io/github/forks/basitali08/customer-churn-prediction?style=social)](https://github.com/basitali08/customer-churn-prediction)

---

**Built by Basit Ali** · [GitHub](https://github.com/basitali08) · [Email](mailto:whoisbasit@gmail.com)  
Customer Analytics Machine Learning · MS Data Science Portfolio
