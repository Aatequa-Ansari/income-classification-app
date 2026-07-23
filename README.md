# 💼 Income Classification using Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg">
  <img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange">
  <img src="https://img.shields.io/badge/Streamlit-Web%20Application-red">
  <img src="https://img.shields.io/badge/License-MIT-green">
</p>

## 📌 Project Overview

Income classification is a supervised machine learning problem that predicts whether an individual's annual income falls into a specific income category based on demographic and employment-related information.

This project develops an end-to-end Machine Learning pipeline for binary classification using data preprocessing, feature engineering, model training, evaluation, and deployment through an interactive Streamlit application. Similar income classification tasks are commonly demonstrated using the UCI Adult (Census Income) dataset. :contentReference[oaicite:0]{index=0}

---

# 🚀 Features

- 📊 End-to-End Machine Learning Pipeline
- 🧹 Data Cleaning & Preprocessing
- 📈 Exploratory Data Analysis (EDA)
- ⚙️ Feature Engineering
- 🤖 Binary Classification Models
- 📉 Model Performance Evaluation
- 💻 Interactive Streamlit Web Application
- 📋 Real-Time Income Prediction

---

# 🧠 Machine Learning Workflow

```text
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Feature Engineering
   │
   ▼
Train-Test Split
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Prediction using Streamlit
```

---

# 📂 Project Structure

```text
Income-Classification-App/
│
├── app.py
├── income_classification.ipynb
├── dataset.csv
├── model.pkl
├── requirements.txt
├── README.md
└── images/
```

---

# 📊 Dataset Features

The model predicts whether a person's annual income belongs to one of two categories.

Example input features may include:

| Feature | Description |
|----------|-------------|
| Age | Age of the individual |
| Workclass | Employment type |
| Education | Highest education level |
| Occupation | Job category |
| Marital Status | Marital status |
| Hours per Week | Weekly working hours |
| Capital Gain | Investment profit |
| Capital Loss | Investment loss |
| Native Country | Country of origin |
| Income | Target Variable |

---

# 🤖 Machine Learning Models

The project can be trained using different classification algorithms, including:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gradient Boosting
- XGBoost (Optional)

The best-performing model is saved and used for prediction.

---

# 📈 Model Evaluation Metrics

The model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

# 🛠️ Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Streamlit
- Joblib

---

# 💻 Installation

Clone the repository

```bash
git clone https://github.com/Aatequa-Ansari/income-classification-app.git
```

Navigate to the project folder

```bash
cd income-classification-app
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---



# 🎯 Future Improvements

- Hyperparameter Optimization
- Explainable AI (SHAP)
- Model Deployment on Cloud
- FastAPI Integration
- Docker Support
- Automated Model Retraining

---

# 👩‍💻 Author

**Aatequa Ansari**

🎓 M.Sc. Industrial Mathematics with Computer Applications

💻 AI / ML Engineer | Data Scientist

🔗 GitHub

https://github.com/Aatequa-Ansari



---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.
