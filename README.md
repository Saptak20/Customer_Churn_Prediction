# 🧠 Customer Churn Prediction App

This Streamlit web app predicts whether a customer will **churn** (i.e., leave a telecom service) based on various demographic and service-related inputs. It uses a trained **Logistic Regression model** to deliver real-time predictions.

---

## 🚀 Live Demo

👉 [Click here to use the deployed app](https://saptak-churn-app.streamlit.app/)

---

## 📊 Dataset

The model is trained using the `customerChurn.csv` dataset containing features like:

- Demographics: `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- Account info: `tenure`, `Contract`, `PaymentMethod`, `PaperlessBilling`
- Services: `PhoneService`, `MultipleLines`, `InternetService`, `TechSupport`, etc.
- Financials: `MonthlyCharges`, `TotalCharges`
- Target: `Churn`

---

## 🧠 Model Details

- 📈 **Algorithm**: Logistic Regression  
- 📦 **Trained on**: Scaled and encoded data  
- ✅ **Model Artifacts**:
  - `logistic_model.pkl`: Serialized model
  - `scaler.pkl`: Feature scaler
  - `encoders/`: Encoded categorical mappings

### Model Performance (on test data):
- **Accuracy**: ~78.9%  
- **Precision**: ~63.4%  
- **Recall**: ~49.2%  
- **F1 Score**: ~55.4%

---

## ⚙️ Tech Stack

- Python, Pandas, NumPy, Scikit-learn  
- Streamlit  
- Jupyter Notebook + VS Code  
- Git & GitHub

---


