📌 Project Overview

This project builds a machine learning model to predict customer churn using the Churn Modelling Dataset.
Customer churn refers to clients who stop using a company’s services.
Accurately predicting churn helps businesses take proactive steps to retain customers and reduce revenue loss.

The project includes:
Full data cleaning and preprocessing
Feature encoding and scaling
Exploratory data analysis (EDA)
Feature selection
Model training and evaluation
Final churn prediction using optimized ML models

📂 Dataset Description

The dataset used is typically structured as follows:
Key Columns
Column	Description
CustomerId	Unique customer identifier
Surname	Customer last name
CreditScore	Customer creditworthiness
Geography	Country of residence
Gender	Male/Female
Age	Customer age
Tenure	Number of years with the bank
Balance	Account balance
NumOfProducts	Number of products held
HasCrCard	Whether customer has a credit card
IsActiveMember	Account activity status
EstimatedSalary	Customer salary
Exited	Target variable (1 = Churned, 0 = Stayed)

📊 Project Workflow

1️⃣ Data Preprocessing
✔ Removed unnecessary columns
✔ Handled missing values
✔ Encoded categorical features using Label Encoding
✔ Scaled numerical features using StandardScaler

2️⃣ Exploratory Data Analysis (EDA)
EDA includes:
Distribution of churn vs non-churn customers
Correlation heatmap
Boxplots comparing key features against churn
Outlier and pattern detection

3️⃣ Feature Selection
Used Sequential Feature Selector (SFS) with Logistic Regression to determine the most impactful features.

4️⃣ Model Training
Models trained include:
Logistic Regression
Random Forest Classifier
XGBoost Classifier
Each model was tested for:
Accuracy
Precision
Recall
F1-score
ROC-AUC score

5️⃣ Results & Performance
Churn model identifies customers at high risk of leaving with strong performance metrics
(e.g., >80% accuracy depending on model selected).
Confusion matrix and ROC curve are provided to visualize performance.

🛠 Technologies Used
Python 3.124
Pandas
NumPy
Matplotlib & Seaborn
Scikit-Learn
XGBoost

🚀 How to Use This Project

Step 1 — Install Dependencies
pip install -r requirements.txt
Step 2 — Run the Notebook or Script
python churn_model.py
Step 3 — Predict Churn
Example:
model.predict([[creditscore, age, balance, num_of_products, ...]])

📈 Output

You will get:
Predicted churn probability
0 = Customer stays
1 = Customer churns
This helps organizations make quick, informed decisions on customer retention.


🤝 Contributing

Pull requests are welcome.
If you'd like to improve the model or add new features, feel free to clone and contribute.

📜 License

This project is open-source under the MIT License.

📧 Contact

For questions, collaborations, or professional inquiries, contact:

Muhammad Abdulkareem

Data Scientist / ML Engineer
https://www.linkedin.com/in/muhammad-abdulkareem-775b83317?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
https://x.com/Danjuma_123?t=lFLZAx-3Dp1UwOC5MDfwAA&s=09
