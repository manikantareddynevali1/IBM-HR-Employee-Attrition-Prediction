# 🧑‍💼 IBM HR Employee Attrition Prediction

Predicting whether an employee is likely to leave a company using classic Machine Learning models, built on the IBM HR Analytics dataset.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview

Employee attrition is a major cost and risk for organizations. This project analyzes the **IBM HR Analytics Employee Attrition** dataset to understand *why* employees leave and to build models that can **predict attrition risk** in advance.

The notebook walks through the full ML pipeline:

- 🧹 Data Cleaning
- 📊 Exploratory Data Analysis (EDA)
- ⚙️ Data Preprocessing & Encoding
- 📏 Feature Scaling
- 🤖 Model Training (Logistic Regression, Decision Tree, Random Forest)
- ✅ Model Evaluation & Comparison

---

## 📂 Dataset

**IBM HR Analytics Employee Attrition & Performance Dataset**
- Source: [Kaggle – IBM HR Analytics Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Records: 1,470 employees
- Target variable: `Attrition` (Yes/No)
- Features: 35 (Age, JobRole, MonthlyIncome, OverTime, WorkLifeBalance, YearsAtCompany, etc.)

---

## 🛠️ Technologies Used

| Category | Tools |
|---|---|
| Language | Python 3 |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Environment | Jupyter Notebook |

---

## 🤖 Models Implemented

| Model | Description |
|---|---|
| Logistic Regression | Baseline linear classifier |
| Decision Tree | Non-linear, interpretable model |
| Random Forest | Ensemble model, best overall performance |

---

## 📈 Evaluation Metrics

Models were evaluated using:

- ✅ Accuracy Score
- 🔢 Confusion Matrix
- 📋 Classification Report (Precision, Recall, F1-score)

---

## 🏆 Results

| Model | Accuracy |
|---|---|
| Logistic Regression | 89.11% |
| Decision Tree | 76.53% |
| **Random Forest** | 86.73% |
 |

> The **Logistic Regression** model achieved the highest prediction accuracy among all evaluated models and generalized best on the test data.



---

## 📁 Project Structure

```
├── HR_Employee_Attrition.ipynb        # Main analysis & modeling notebook
├── WA_Fn-UseC_-HR-Employee-Attrition.csv  # Dataset
├── requirements.txt                   # Python dependencies
└── README.md                          # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/manikantareddynevali1/IBM-HR-Attrition-Prediction.git
cd IBM-HR-Attrition-Prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
```bash
jupyter notebook HR_Employee_Attrition.ipynb
```

---

## 🔮 Future Improvements

- 🔧 Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
- 📉 ROC-AUC Curve analysis
- 🔁 Cross-validation for more robust evaluation
- ⭐ Feature importance ranking (SHAP / permutation importance)
- 🌐 Deploy as a web app using **Streamlit** or **Flask**
- ⚖️ Handle class imbalance (SMOTE)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues) or open a pull request.


---

## 👤 Author

**Mani Reddy**
- GitHub: [@your-username]([https://github.com/your-username](https://github.com/manikantareddynevali1])
- LinkedIn: [Your LinkedIn](https://www.linkedin.com/in/mani-reddy-05506541a?utm_source=share_via&utm_content=profile&utm_medium=member_android)

---



