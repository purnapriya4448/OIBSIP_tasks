📈 Sales Prediction Using Python
🎯 Internship Task – Oasis Infobyte
📝 Overview
This project is part of the Oasis Infobyte Internship Program. The goal of this task is to build a machine learning model that can predict future sales based on several input features like advertising spend, target segment, and marketing platform.

Sales forecasting is a key element in business strategy, and this project demonstrates how data science can be used to generate actionable insights from historical sales data.

🧪 Project Workflow
1. Data Loading & Preprocessing
Loaded the dataset using pandas
Cleaned missing or inconsistent data
Encoded categorical variables
Scaled numerical features where necessary

2. Exploratory Data Analysis (EDA)
Analyzed data distributions and trends
Visualized sales across different platforms and segments
Found correlations between features using heatmaps and pairplots

3. Feature Engineering
Selected key influencing features
Created dummy variables for categorical data

4. Model Building
Applied machine learning models like:
Linear Regression
Random Forest Regressor
Split data into training and testing sets
Evaluated models using:
R² Score
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)

5. Results & Visualization
Predicted future sales based on test data
Plotted actual vs predicted sales values
Displayed feature importance for business insights

📂 Dataset Features (Example)
Feature	Description
Sales	Target variable: units sold
Ad_Spend_TV	Amount spent on TV ads
Ad_Spend_Social	Amount spent on social media ads
Platform	Platform used for campaign (e.g., Instagram)
Target_Segment	Customer demographic group (e.g., Youth, Adults)

🛠️ Tools & Libraries Used
Python
Pandas, NumPy – Data manipulation
Matplotlib, Seaborn – Data visualization
Scikit-learn – Machine learning
Jupyter Notebook / Google Colab – Development environment

📈 Model Performance
Model	R² Score	MAE	RMSE
Linear Regression	0.85	2.3	3.1
Random Forest Regressor	0.92	1.7	2.4
Values may vary based on the dataset version used.

🙌 Acknowledgement
This project was completed as part of the Oasis Infobyte Internship Program.
Special thanks to the team at Oasis Infobyte for providing this valuable learning opportunity to apply machine learning to real-world business problems.

📌 How to Run
Clone the repository:
git clone https://github.com/purnapriya4448/sales-prediction.git

Install the requirements:
pip install -r requirements.txt
Open the notebook and run:

jupyter notebook sales_prediction.ipynb
📬 Contact
For any queries or suggestions, feel free to connect via GitHub or LinkedIn.
