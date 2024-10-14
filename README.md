# Customer_Churn_Prediction_Based_On_Subscription_Service

Customer Churn Prediction Based on Subscription Service Using Machine Learning and Streamlit
Project Overview
This project aims to predict customer churn for a subscription-based service using machine learning models. A Streamlit app is built to allow users to input various features and get predictions on whether a customer will churn or not.

Installation
Clone the repository:

git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction
Set up a virtual environment:

python3 -m venv venv
source venv/bin/activate   # On Windows use `venv\\Scripts\\activate`
Install the required packages:

pip install -r requirements.txt
Data
The dataset used for this project is expected to be named train.csv and should be placed in the root directory of the project. It contains various features related to customer subscriptions.

Usage
Run the Streamlit app:

streamlit run index.py
Open your web browser and go to http://localhost:8501 to access the app.

Input the required features in the form provided in the Streamlit app to predict customer churn.

Modeling
The project employs the LightGBM (LGBM) classifier to predict customer churn. The following steps are performed:

Data loading and preprocessing
Splitting data into training and testing sets
Resampling the training data using SMOTE
Training the LGBM model
Streamlit App
The Streamlit app is configured with a user-friendly interface, allowing users to input various features to get churn predictions. It includes functionalities to:

Input numerical and categorical features
Preprocess and standardize input data
Predict customer churn based on the trained model
Background and Styling
The app includes custom styling and a background image to enhance the user experience.

Contributing
If you wish to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.
