# 🏦 Bank Churn Prediction - Neural Network Project
## 📌 Overview
This project applies a neural network classifier to predict customer churn — whether a customer will leave the bank — using historical customer data. 
Predictive insights generated here are key to helping banks improve customer retention by identifying churn risks early.

## 🎯 Objective
Build and evaluate a neural network-based classifier to:
<ul>
<li>Predict if a customer will churn or stay.</li>

<li>Explore key variables driving customer behavior.</li>

<li>Implement and compare different model versions for performance enhancement.</li>
</ul>

## 📁 Dataset
Source: Kaggle - Bank Customer Churn Modeling

Rows: 10,000
Columns: 14
Key Features:
<ul>
<li>CreditScore, Geography, Gender, Age, Tenure, Balance, EstimatedSalary, etc.</li>

<li>Exited is the target variable (1 = churned, 0 = stayed)</li>
</ul>

## 🧰 Tools & Technologies
<ul>
<li>Python 3</li>

<li>Pandas, NumPy</li>

<li>Matplotlib, Seaborn</li>

<li>Scikit-learn</li>

<li>TensorFlow / Keras</li>

<li>Jupyter Notebook</li>
</ul>

## 🔍 Project Steps


1. Data Preparation
<ul>
<li>Loaded dataset and dropped identifiers (e.g., CustomerId, Surname, RowNumber)</li>

<li>Encoded categorical variables using one-hot encoding</li>

<li>Split into training and test sets</li>

<li>Scaled features using StandardScaler</li>
</ul>

2. Model Building
<ul>
<li>Model 1: Baseline neural network</li>

<li>Model 2: Improved neural network with optimized layers, dropout, and batch normalization</li>
</ul>

3. Model Evaluation
<ul>
<li>Predicted probabilities converted to binary using a threshold of 0.5</li>

<li>Evaluated using:</li>
<ul>
<li>Accuracy Score</li>

<li>Confusion Matrix</li>
</ul></ul>

## 📈 Results
Model	Accuracy	Notes
Baseline NN	~X.XX	Basic 2-layer NN
Improved NN	~X.XX	Tuned layers, dropout, early stopping
Replace X.XX with your actual results.

## 📊 Visuals
<ul>
<li>Training vs Validation Accuracy plots</li>

<li>Confusion Matrix heatmaps</li>

<li>Feature distributions by churn status</li>
</ul>

## 💡 Business Insights
<ul>
<li>Age and account balance were significant indicators of churn.</li>

<li>Customers from certain geographies had higher churn rates.</li>

<li>The improved model gave better generalization performance and reduced overfitting.</li>
</ul>

## 🔁 Improvements Considered
<ul>
  
<li>Hyperparameter tuning using Grid Search or Random Search</li>

<li>Use of different activation functions or optimizers</li>

<li>Integration with advanced ML models (e.g., XGBoost) for ensemble comparison</li>

</ul>

## 📂 Repository Structure
Copy
Edit
bank-churn-prediction/

├── bank.csv

├── Project_Solution_Notebook_Bank_Churn_Prediction.ipynb

├── Bank_Churn_Prediction_Anyakwu,_Chukwuemeka_Isaac.ipynb

├── bankchurn.pdf

├── bankChurn.docx

├── BChurn.html

├── README.md

## Additional Resource

## 👨‍💻 Author
Chukwuemeka Isaac Anyakwu
Project for Great Learning Academy

