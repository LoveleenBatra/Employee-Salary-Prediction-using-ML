# Employee-Salary-Prediction-using-ML
📌 Project Overview
This project uses classification algorithms to predict employee income classes (<=50K or >50K) using features such as:
Age
Education
Workclass
Occupation
Gender
Hours-per-week
Capital gain/loss, etc.
It includes complete data preprocessing, outlier handling, model comparison, and deployment using Streamlit and Ngrok.

🚀 Features
Data cleaning and preprocessing (missing values, outliers, encoding)
Multiple ML model training (Logistic Regression, Random Forest, SVM, etc.)
Accuracy comparison using bar charts
Best model saved for future predictions
Streamlit app for user-friendly predictions
Deployed using Ngrok (for use in Colab)

🛠️ Tech Stack & Libraries
Python 3.8+
pandas, numpy – Data manipulation
scikit-learn – ML models and preprocessing
matplotlib – Visualization
streamlit – Web app deployment
pyngrok – Public URL for Streamlit app in Colab
joblib – Model saving/loading

📁 Project Structure
├── app.py               # Streamlit app
├── best_model.pkl       # Trained ML model
├── adult 3.csv          # Dataset
├── model_training.py    # Code for training and saving models
├── README.md            # Project overview
⚙️ How to Run the Project Locally
⚠️ Make sure Python is installed (3.8 or later)

1. Clone the Repository
2. Install Required Packages
pip install pandas numpy scikit-learn matplotlib streamlit pyngrok joblib
4. Run the Streamlit App
streamlit run app.py
You’ll see a link in the terminal. Open it in your browser.

✅ How It Works
User enters employee details in the Streamlit UI
Inputs are converted into a DataFrame with proper feature encoding
The saved model (best_model.pkl) predicts the salary class
Result is displayed: <=50K or >50K
