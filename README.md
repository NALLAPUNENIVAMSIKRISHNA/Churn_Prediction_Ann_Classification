# Churn_Prediction_Ann_Classification

This project demonstrates a customer churn prediction model using Artificial Neural Networks (ANNs). It includes preprocessing steps, model training, and a deployed web application using Streamlit. The model predicts whether a customer is likely to churn based on various features such as credit score, geography, gender, and more.

Features

Data Preprocessing:
  Encoding categorical variables using Label Encoding and One-Hot Encoding.
  Scaling numerical features using StandardScaler.
Model Training:
  Built and trained an ANN using TensorFlow and Keras.
  Used callbacks for early stopping and TensorBoard for visualization.
Deployment:
  Integrated with a Streamlit app for an interactive user interface.
  Hosted on Streamlit Cloud for easy accessibility.

Main Files in the Repository
1. Churn_prediction_ANN_Classification.ipynb
  Data preprocessing steps.
  ANN model training and evaluation.
  Saving encoders, scalers, and the trained model for deployment.

2. app.py
  A Streamlit-based web app for predicting customer churn.
  Interactive UI for user inputs such as age, gender, geography, balance, etc.
  Integration with the trained model to predict churn probability.

Deployment
The Streamlit application is live and can be accessed at the link here : https://churnpredictionannclassification-j32uxueskatwhwh3yybyq6.streamlit.app/

How to Run Locally :
  Clone repository
  Install dependencies (pip install -r requirements.txt)
  Run the Streamlit app (streamlit run app.py)
  
Usage
  Open the application in your browser.
  Fill in the required fields like Geography, Gender, Age, Balance, etc.
  Click "Predict" to get the churn probability and the prediction result as attached in screenshot.
  
Fill the details:
  ![image](https://github.com/user-attachments/assets/5abf81ee-f6f1-4fa3-a9cb-c31784700c48)
Prediction at the end as Likey to churn or not as attached in screenshot
  ![image](https://github.com/user-attachments/assets/484e98be-bab8-469f-9e26-055ac3106af5)

  Use the app to input customer details and view predictions.
Thank you.
