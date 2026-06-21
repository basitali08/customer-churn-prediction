# Customer Churn Prediction

## 📋 Project Overview

This project predicts whether a customer will leave a telecom company (churn) based on their usage patterns, demographics, and account information. Customer churn is a critical business metric, and predicting it helps companies take proactive measures to retain customers.

## 🎯 Business Objective

- Identify customers likely to churn
- Understand key factors influencing churn
- Build a predictive model with high accuracy
- Provide actionable insights for customer retention

## 📊 Dataset

The dataset contains customer information including:
- **Demographics**: gender, age, partner, dependents
- **Services**: phone, internet, streaming, tech support
- **Account**: contract type, payment method, monthly/total charges
- **Target**: Churn (Yes/No)

## 🛠️ Technologies Used

- Python 3.8+
- Pandas & NumPy (Data Manipulation)
- Matplotlib & Seaborn (Visualization)
- Scikit-learn (Machine Learning)
- Jupyter Notebook

## 📁 Project Structure

```
Customer-Churn-Prediction/
├── README.md
├── requirements.txt
├── customer_churn_prediction.ipynb
├── data/
│   └── telecom_churn.csv
├── images/
│   └── (visualization outputs)
└── models/
    └── (saved models)
```

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook:
```bash
jupyter notebook customer_churn_prediction.ipynb
```

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 82% | 68% | 55% | 61% |
| Random Forest | 84% | 72% | 58% | 64% |
| Gradient Boosting | 86% | 75% | 62% | 68% |

## 📝 Key Findings

1. **Contract Type**: Month-to-month contracts have highest churn rate
2. **Tenure**: Customers with < 12 months tenure are more likely to churn
3. **Internet Service**: Fiber optic users have higher churn
4. **Payment Method**: Electronic check users churn more

## 👨‍💻 Author

Created as part of Data Science Project Portfolio

## 📄 License

This project is open source and available under the MIT License.
