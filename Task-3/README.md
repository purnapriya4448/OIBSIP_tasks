🚗 Car Price Prediction using Machine Learning
This project is part of my Data Science Internship at Oasis Infobyte. The goal is to build a machine learning model that can predict the selling price of a used car based on features like year of manufacture, fuel type, transmission, and kilometers driven.

📌 Objective
To develop a regression-based machine learning model that provides accurate price predictions for used cars, helping sellers and buyers make informed decisions.

🔍 Key Features
📅 Car Age Calculation from the manufacturing year

⛽ Categorical Features handled through one-hot encoding

🤖 Multiple Models Tested – including Linear Regression and Random Forest

📈 Evaluation Metrics – R² score, MAE, feature importance analysis

📊 Dataset Overview
Column Name	Description
Car_Name	Name of the car
Year	Year of purchase
Selling_Price	Price the car is being sold for
Present_Price	Current ex-showroom price of the car
Kms_Driven	Distance driven
Fuel_Type	Fuel category (Petrol, Diesel, CNG)
Seller_Type	Type of seller (Individual or Dealer)
Transmission	Manual or Automatic
Owner	Number of previous owners

⚙️ Technologies Used
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook / Google Colab

🧪 Workflow
Data Cleaning

Removed irrelevant columns like Car_Name

Derived new feature Car Age

Exploratory Data Analysis (EDA)

Visualized feature distributions and correlations

Feature Engineering

Handled categorical variables using encoding

Model Training

Applied Linear Regression and Random Forest Regressor

Model Evaluation

Used R² Score and Mean Absolute Error for performance measurement

✅ Results
Achieved a high accuracy with R² Score > 0.85

Key influencing features: Present_Price, Car_Age, Fuel_Type

📂 Repository Structure
📁 car-price-prediction/
├── 📊 car_data.csv                # Dataset
├── 📓 Car_Price_Prediction.ipynb # Main code notebook
├── 📄 README.md                   # Project documentation
├── 📜 requirements.txt            # Required libraries
└── 💾 model.pkl (optional)        # Trained model (if saved)
🎯 What I Learned
Data preprocessing and handling real-world datasets

Feature encoding and model evaluation techniques

Regression model building and performance tuning

🔗 Demo Links
📂 GitHub Repo:https://github.com/purnapriya4448/OIBSIP_tasks/edit/main/Task-3/README.md

📢 Developed as part of Oasis Infobyte Internship Program
👩‍💻 Author: Purnapriya Tammana










