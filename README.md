# 📉 Customer churn Prediction
This project aims to predict customer churn using machine learning techniques. By analyzing customer data, we can identify patterns that indicate whether a customer is likely to discontinue a service.

# 🧠 Objective
Develop a predictive model that classifies customers as likely to churn or not, enabling businesses to take proactive measures to retain customers.

# 📁 Project Structure

├── churn_model.ipynb          # Jupyter notebook with data analysis and model training

├── data.csv                   # Dataset containing customer information

├── customer_churn_model.pkl   # Serialized trained model

├── encoders.pkl               # Serialized label encoders for categorical variables

# 🛠️ Tools & Libraries
Python

pandas

scikit-learn

Jupyter Notebook

# 📊 Dataset
The dataset (data.csv) includes various features related to customer demographics and service usage. Each record represents a customer, with a target variable indicating churn status.


# 📈 Model Training & Evaluation
The notebook walks through:

Data loading and exploration

Preprocessing steps (handling missing values, encoding categorical variables)

Splitting data into training and testing sets

Training a machine learning model

Evaluating model performance using appropriate metrics

# 💾 Model & Encoders
customer_churn_model.pkl: The trained machine learning model saved using joblib or pickle.

encoders.pkl: The label encoders used for transforming categorical variables during preprocessing.

These files can be loaded for making predictions on new data.

# 👩‍💻 Author
Aashita Asati – GitHub 
#  
