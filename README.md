# Bank-Marketing-Prediction-using-Decision-Tree-Classifier
Decision Tree Classifier using the Bank Marketing Dataset to predict whether a customer will subscribe to a term deposit.

# 🌳 Customer Purchase Prediction – Decision Tree Classifier

🔍 **Objective:**  
Build a Decision Tree model to predict if a customer will purchase a product/service based on demographic and behavioral data.

📁 **Dataset:**  
[Bank Marketing Dataset – UCI]

🎯 **Target Variable:**  
`y` – whether the client subscribed to a term deposit

📊 **Features:**
- age, job, marital status, education, contact type, month, campaign, etc.

🛠️  Workflow
📂 Dataset Loading
Load the Bank Marketing dataset (bank.csv) into a pandas DataFrame.

🧹 Data Preprocessing

Parse semicolon-separated values

Encode categorical features using Label Encoding

📊 Feature & Target Separation

Input features: all columns except y

Target variable: y

🔀 Train-Test Split
Split the dataset into training and testing sets (80/20).

🌲 Model Building
Train a Decision Tree Classifier on the training data.

📈 Model Evaluation
Evaluate accuracy, precision, recall, F1-score, and confusion matrix.

📉 Feature Importance Visualization
Plot top contributing features to understand decision-making.

📸 Screenshot Generation
Automatically saves feature importance plot to the /screenshots folder.
