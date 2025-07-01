# TITANIC-SURVIVAL-PREDICTION


Use the Titanic dataset to build a model that predicts whether a
passenger on the Titanic survived or not. This is a classic beginner
project with readily available data.
The dataset typically used for this project contains information
about individual passengers, such as their age, gender, ticket
class, fare, cabin, and whether or not they survived.




#=============================================================================

### 🚢 Titanic Survival Prediction - CodeSoft Task 1
This project is a comprehensive end-to-end machine learning pipeline developed to predict passenger survival on the Titanic using classical ML models. It was built as part of the CodeSoft Internship Task 1.

🔍 Overview
The notebook performs:

Data acquisition and exploration

Feature engineering and preprocessing

Model building with multiple algorithms

Evaluation with detailed metrics and visualizations

Hyperparameter tuning using GridSearchCV

Feature importance analysis

Predictions on new data

📁 Dataset
Dataset used: Titanic Dataset from DataScienceDojo

📊 Models Used
Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

🧪 Features & Engineering
Extracted titles from names

Created FamilySize and IsAlone indicators

Binned Age and Fare into categories

One-hot encoded categorical variables

🧼 Preprocessing
Handled missing values using median and constant strategies

Used ColumnTransformer and Pipeline for clean ML workflow

Applied StandardScaler for numerical features

🧠 Model Evaluation
Each model was evaluated based on:

Accuracy, Precision, Recall, F1-Score

ROC-AUC Score

Confusion Matrix and Classification Report

📌 Best Model: Random Forest
Accuracy: ~83%

Top Features: Sex, Fare, Title, Age

📈 Visualizations
Survival by gender, class, age

Correlation heatmap

ROC and Precision-Recall curves

Top 20 feature importances

🔧 Hyperparameter Tuning
Used GridSearchCV to optimize the Random Forest classifier parameters.

🚀 Prediction on New Data
The pipeline supports making predictions for custom passenger profiles.

📌 Conclusion & Next Steps
Random Forest outperformed other models in this use case.

Model can be deployed using Flask or Streamlit.

Can be extended with Neural Networks for further improvements.

Ready to be wrapped into an API for production use.

🧰 Tech Stack
Python

Pandas, NumPy, Seaborn, Matplotlib

scikit-learn

📄 License
This project is part of CodeSoft Internship and available for educational use.
