# Heartdisease1
❤️ Heart Disease Prediction using Machine Learning
📌 Project Overview
  Developed a Machine Learning model to predict the likelihood of heart disease.
  Performed complete data preprocessing, visualization, model training, and evaluation.
  Compared multiple classification algorithms to identify the best-performing model.
  Saved the trained model for future deployment.
📂 Dataset
  Heart Disease Dataset (heart.csv)
  Target Variable: HeartDisease
  Contains patient medical information such as:
  Age
  Sex
  Chest Pain Type
  Resting Blood Pressure
  Cholesterol
  Fasting Blood Sugar
  Resting ECG
  Maximum Heart Rate
  Exercise-Induced Angina
  Oldpeak
  ST Slope
🛠 Data Preprocessing
  Checked dataset shape and information.
  Verified missing values.
  Checked duplicate records.
  Replaced invalid 0 values in:
  Cholesterol
  Resting Blood Pressure
  Applied One-Hot Encoding to categorical features.
  Standardized numerical features using StandardScaler.
📊 Exploratory Data Analysis (EDA)
  Distribution plots (Histogram + KDE)
  Count plots
  Box plots
  Violin plots
  Correlation Heatmap
  Target class distribution analysis
🤖 Machine Learning Models Used
  Logistic Regression
  K-Nearest Neighbors (KNN)
  Gaussian Naive Bayes
  Decision Tree Classifier
  Support Vector Machine (RBF Kernel)
📈 Model Evaluation

  Models were evaluated using:
   Accuracy Score
   F1 Score
   Classification Report
💾 Model Saving

 The following files were saved using Joblib:
  KNN_heart.pkl
  scaler.pkl
  columns.pkl
🧰Technologies Used
  Python
  NumPy
  Pandas
  Matplotlib
  Seaborn
  Scikit-learn
  Joblib
📁 Project Structure
  Heart-Disease-Prediction/
  │── heart.csv
  │── Heartdisease1.ipynb
  │── KNN_heart.pkl
  │── scaler.pkl
  │── columns.pkl
  │── requirements.txt
  │── README.md
