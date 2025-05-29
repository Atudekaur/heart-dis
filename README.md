A machine learning project to predict the likelihood of heart disease based on various clinical and demographic features. This project demonstrates data preprocessing, model training, evaluation, and deployment techniques using Python and popular machine learning libraries.

 Dataset
The model is trained on the UCI Heart Disease dataset, which includes features such as:

Age

Sex

Chest Pain Type (cp)

Resting Blood Pressure (trestbps)

Cholesterol (chol)

Fasting Blood Sugar (fbs)

Resting ECG Results (restecg)

Max Heart Rate Achieved (thalach)

Exercise Induced Angina (exang)

ST Depression (oldpeak)

Slope of Peak Exercise ST Segment (slope)

Number of Major Vessels (ca)

Thalassemia (thal)

🛠️ Tools & Technologies
Python 🐍

Pandas & NumPy

Scikit-learn

Matplotlib & Seaborn

Jupyter Notebook

Streamlit (for deployment - optional)

📈 Models Used
Logistic Regression

Random Forest

K-Nearest Neighbors

Support Vector Machine (SVM)

The models were evaluated using metrics like accuracy, precision, recall, and ROC-AUC.

✅ Features
Exploratory Data Analysis (EDA)

Data Cleaning & Feature Engineering

Model Training & Comparison

Hyperparameter Tuning

Confusion Matrix & ROC Curve Visualization

Web App (optional: using Streamlit)

🚀 How to Run
bash
Copy
Edit
# Clone the repo
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook


🧠 Prediction Output
Given input values such as age, chest pain type, and cholesterol levels, the model predicts whether the patient is likely to have heart disease (1) or not (0).
