# 🧠 Customer Churn Prediction

This project builds and deploys a **Logistic Regression model** to predict whether a customer is likely to **churn (leave)** a telecom service provider. It includes:

- Data preprocessing
- Model training
- Performance evaluation
- Streamlit-based web app for live predictions
- GitHub and Streamlit Cloud deployment

---

## 📊 Dataset

The dataset `customerChurn.csv` contains the following columns:

- `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- `tenure`, `PhoneService`, `MultipleLines`
- `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`
- `StreamingTV`, `StreamingMovies`, `Contract`, `PaperlessBilling`, `PaymentMethod`
- `MonthlyCharges`, `TotalCharges`, `Churn (Target)`

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy, Scikit-learn
- Streamlit
- VS Code + Jupyter Notebook
- Git, GitHub

---

## 📌 Project Structure
Customer_Churn_Prediction/
├── app.py # Streamlit app
├── churn_model.ipynb # Model training and EDA notebook
├── customerChurn.csv # Dataset
├── logistic_model.pkl # Trained model
├── scaler.pkl # Scaler object
├── encoders/ # Encoded label files
├── requirements.txt # Dependencies
└── README.md # Project documentation

yaml
Copy code

---

## 🚀 How to Run the App Locally

1. **Clone the repository:**

```bash
git clone https://github.com/<your-username>/Customer_Churn_Prediction.git
cd Customer_Churn_Prediction
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy code
streamlit run app.py
✅ Model Performance
On test data (80/20 split):

Accuracy: ~78.9%

Precision: ~63.4%

Recall: ~49.2%

F1 Score: ~55.4%

Evaluated using accuracy, precision, recall, F1-score, and confusion matrix.

🌐 Live Demo
🔗 Click here to open the Streamlit app
(Replace with your actual deployed URL after deploying)

📃 License
This project is open-source and available under the MIT License.

yaml
Copy code

---

## ✅ What to Do:

1. Save the above content into a file named `README.md` in your project root folder.
2. Commit and push to GitHub:

```bash
git add README.md
git commit -m "Added README file"
git push origin main
