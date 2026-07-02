# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a person is at **high risk or low risk of heart disease** using Machine Learning. A **K-Nearest Neighbors (KNN)** classifier was trained on a heart disease dataset using patient health information.

The project includes an interactive **Streamlit web application** where users can enter medical details, receive instant heart disease risk predictions, and view results through a user-friendly interface.



## 🚀 Features

- Predict heart disease risk
- Interactive Streamlit web application
- Real-time prediction
- Easy-to-use input interface
- Machine Learning-based classification



## 🛠 Technologies Used

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Joblib



## 📂 Dataset

The project uses the **Heart Disease Prediction Dataset**.

### Features

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak
- ST Slope

### Target

- **0 → Low Risk of Heart Disease**
- **1 → High Risk of Heart Disease**



## 📊 Machine Learning Workflow

1. Data Collection
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Data Cleaning
5. Feature Encoding
6. Feature Scaling
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Best Model Selection
11. Model Serialization using Joblib
12. Streamlit Web Application Development
13. Deployment



## 🤖 Model Used

**K-Nearest Neighbors (KNN)**

The KNN algorithm predicts heart disease risk by comparing a patient's medical attributes with the nearest training examples.



## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report



## 📁 Project Structure

HeartDiseasePrediction/

│── app.py

│── HeartDiseasePrediction.ipynb

│── KNN_heart.pkl

│── scaler.pkl

│── columns.pkl

│── requirements.txt

│── README.md



## ▶️ Installation

### Clone Repository

```bash
git clone https://github.com/TamaliM174/Heartdisease1.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Streamlit

```bash
streamlit run app.py
```



## 📱 Application Workflow

- Enter patient details
- Click **Predict**
- View prediction result
- Displays **High Risk** or **Low Risk** of heart disease



## 🎯 Future Improvements

- Display prediction probability
- Risk score visualization
- Interactive health charts
- Explainable AI (Feature Importance)
- Cloud deployment
- Support for batch prediction



## 👩‍💻 Author

**Tamali Mahapatra**

Machine Learning | Data Science | Python
