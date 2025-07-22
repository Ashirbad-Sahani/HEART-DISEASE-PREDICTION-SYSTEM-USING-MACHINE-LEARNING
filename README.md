🫀 Early Diagnosis of Heart Disease in India using Predictive Machine Learning Techniques
This project focuses on the early detection of heart disease using various machine learning models and explainable AI (XAI) techniques. It uses a real-world heart disease dataset, applies preprocessing and feature engineering, trains multiple classification algorithms, compares their performance, and builds an interactive prediction interface.

📌 Objective
To develop a machine learning-based predictive system that can assist in the early diagnosis of heart disease using health parameters common in the Indian demographic.

📊 Features
📂 Data Preprocessing & Exploration
Log transformation, missing value checks, and visual exploration using histograms, heatmaps, and correlation analysis.

🤖 Models Trained

Logistic Regression

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Decision Tree (with GridSearchCV)

Random Forest

Gradient Boosting

XGBoost

🎯 Evaluation Metrics

Accuracy

Confusion Matrix

Classification Report

ROC-AUC Curve

Bar Chart Comparisons

📈 Model Explainability (XAI)

SHAP visualizations (Force plot, Summary plot, Beeswarm)

💾 Model Serialization

Best-performing model (Random Forest) saved using pickle

🧑‍💻 Interactive Prediction UI

Built using ipywidgets for real-time prediction of heart disease from user input

🔧 Technologies Used
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

XGBoost, SHAP

IPython Widgets

Google Colab

🧠 How It Works
Load and explore the heart disease dataset.

Apply necessary transformations and split into train-test sets.

Train multiple models and compare them visually and statistically.

Choose the best model (Random Forest) for prediction.

Visualize important features and model behavior using SHAP.

Create a GUI for user input and real-time prediction.

📈 Results
Highest Accuracy: ~90% with Random Forest and XGBoost

Most Interpretable Model: Random Forest with SHAP explanations

User-Friendly Interface: Helps users understand their risk factors interactively

🧪 Run it Yourself
bash
Copy
Edit
# Clone the repo
git clone https://github.com/yourusername/heart-disease-prediction.git

# Install dependencies
pip install -r requirements.txt
Or open in Google Colab to try the UI directly.

📍 Future Improvements
Integration with web UI (Flask/Streamlit)

More robust outlier detection

Deploy as an API or web app

Use more comprehensive Indian health datasets

👨‍💻 Author
Ashirbad Sahani
LinkedIn | GitHub
