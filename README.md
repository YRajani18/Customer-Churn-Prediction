# Customer Churn Prediction 📊

This project predicts **telecom customer churn** using Machine Learning models such as **Logistic Regression** and **Random Forest** in Google Colab.  
The goal is to identify customers likely to leave the service and help companies improve retention strategies.  

---

## 📂 Dataset
- Dataset: **Telecom Customer Churn**  
- Source: [Telecom_customer_churn.csv](https://raw.githubusercontent.com/dsrscientist/DSData/master/Telecom_customer_churn.csv)  
- Rows: 7,043  
- Features: Gender, SeniorCitizen, Partner, Dependents, tenure, PhoneService, InternetService, OnlineSecurity, OnlineBackup, TechSupport, StreamingTV, StreamingMovies, Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges.  
- Target: **Churn** (Yes = customer left, No = customer stayed)  

---

## 🛠 Steps in the Project
1. **Data Cleaning & Preprocessing**  
   - Handled missing values  
   - Converted categorical variables into numeric (One-Hot Encoding)  
   - Scaled numerical features  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of churned vs retained customers  
   - Effect of tenure, monthly charges, and contract type on churn  

3. **Model Training**  
   - Logistic Regression  
   - Random Forest Classifier  

4. **Model Evaluation**  
   - Accuracy  
   - Confusion Matrix  
   - Classification Report (Precision, Recall, F1-score)  

---

## 📈 Results
- **Logistic Regression Accuracy**: ~80%  
- **Random Forest Accuracy**: ~85%  

(Random Forest performed better due to capturing non-linear relationships.)  

---

## 🖥 Tools & Libraries
- Python (Google Colab)  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 🚀 How to Run
1. Clone this repo:  
   ```bash
   git clone https://github.com/YRajani18/Customer-Churn-Prediction.git
