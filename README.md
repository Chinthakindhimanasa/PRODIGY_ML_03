# 🏦 Personal Loan Prediction using Support Vector Machine (SVM)

## 📖 Project Description
This project implements a **Support Vector Machine (SVM)** model to classify whether a customer will accept a personal loan offer. 

The model is trained on the UniversalBank dataset and predicts the target variable **Personal Loan (0 = No, 1 = Yes)** using customer demographic and financial information.

---

## 📂 Dataset
- Dataset Name: UniversalBank
- Source: Kaggle
- Target Column: Personal Loan

### Features Used:
- Age
- Experience
- Income
- Family
- Education
- Mortgage
- Securities Account
- CD Account
- Online
- CreditCard

---

## ⚙️ Project Workflow

1. Data Loading
2. Data Cleaning (Removed ID & ZIPCode)
3. Handling Missing Values
4. Feature Scaling using StandardScaler
5. Train-Test Split (80%-20%)
6. Model Training using SVM
7. Model Evaluation

---

## 🤖 Machine Learning Model

Algorithm Used:
- Support Vector Machine (SVM)

Kernels Tested:
- Linear
- RBF
- Polynomial
- Sigmoid

---

## 📊 Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- ROC Curve
- Cross Validation

---

## 📈 Visualizations

- Loan Approval Distribution
- Income vs Loan Approval
- Confusion Matrix Heatmap
- ROC Curve
- Kernel Comparison
- C vs Accuracy
- Gamma vs Accuracy

---

## 🏆 Results

The RBF kernel achieved the best accuracy among all tested kernels.  
Feature scaling significantly improved model performance.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

---

## 🚀 How to Run the Project

1. Clone the repository:
   git clone https://github.com/your-username/your-repo-name.git

2. Install required libraries:
   pip install pandas numpy scikit-learn matplotlib seaborn

3. Run the Python script:
   python svm_model.py

---

## 📌 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Compare with Logistic Regression & Random Forest
- Deploy using Flask/Streamlit
- Add feature importance analysis

---

## 👩‍💻 Internship Project

This project was developed as part of a Machine Learning internship assignment.
🔥 Extra Tip for GitHub

Add these files to make your repo look professional:

📁 Personal-Loan-SVM
 ├── svm_model.py
 ├── README.md
 ├── requirements.txt
 └── dataset_info.txt
