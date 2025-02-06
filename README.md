# Laptop_Price_Predictor
"This project focuses on building a machine learning-based web application to predict laptop prices based on various specifications. The application utilizes Random forest regression models, optimized for key laptop features such as processor, RAM, storage, GPU, and brand. This system helps users make informed decisions when purchasing laptops by providing accurate price estimates."

# Features
Dataset: The dataset was curated from Kaggle, including diverse laptop specifications from multiple brands (Dell, HP, Apple, Asus, Lenovo, etc.), ensuring comprehensive insights for accurate predictions.

Machine Learning Model: Random forest regression models are employed for feature selection and regularization, minimizing overfitting and improving prediction accuracy.

User-Friendly Interface
Frontend: Built with HTML, CSS, and JavaScript for an interactive and responsive user experience.

Backend: Developed using Django for robust server-side logic and secure data handling.

SQLite Database: Efficiently stores user inputs and model outputs, seamlessly integrating with the web application.

Brand and Specification Support: Allows users to select key laptop attributes (brand, processor, RAM, storage type, GPU, screen size, etc.), ensuring predictions are tailored to the selected specifications.

Data Visualization: Key insights, such as price trends and laptop specifications' impact on price, are presented through interactive graphs and charts.

# How It Works
Users provide laptop specifications through an intuitive form on the web application.

The application processes the data and passes it to the corresponding trained Lasso or Ridge regression model.

The model returns the predicted laptop price, displayed in a user-friendly format.

Visual aids help users understand the factors influencing the prediction.

# Technology Stack
Frontend: HTML, CSS, JavaScript

Backend: Django

Machine Learning Models: Random forest Regression

# Requirements for the Project
Software Dependencies

Django Framework Version: 4.x or higher (Leverages modern Django features like class-based views and enhanced ORM capabilities).

Python Version: 3.10 or higher (Ensures compatibility with advanced libraries and features).

# Libraries Required
NumPy: >=1.21.0 → For numerical operations in regression models.

pandas: >=1.3.0 → For data manipulation and preprocessing.

scikit-learn: >=1.0.0 → For implementing Lasso and Ridge regression models.

joblib: >=1.2.0 → For saving and loading serialized models.

For saving and loading serialized models.

Deployment Requirements

Gunicorn: >=20.0.0

WhiteNoise: >=5.3.0 (for serving static files in production).

# Steps or Commands to Run the Project
1.Download the project zip file and extract it.

2.Open the extracted folder in VSCode.

3.Open the terminal in VSCode.

4.Navigate to the project directory by running:bash

5.Copy code

6.cd laptop

7.Start the Django development server by running: bash

8.Copy code

9.python manage.py runserver  

10.Open the provided URL in a browser to access the application.

