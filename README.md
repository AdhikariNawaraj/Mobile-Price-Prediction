📱 Mobile Price Prediction

📌 Overview

This project aims to predict the price range of mobile phones based on various hardware and feature specifications using machine learning models. The dataset includes 21 features such as battery capacity, RAM, screen resolution, internal memory, and network capabilities. The target variable (price_range) is categorized into low, medium, high, and very high price classes.

🏗 Project Workflow

Data Preprocessing:
Handling missing values & duplicates
Correcting inconsistencies (e.g., screen resolution)
Feature scaling using StandardScaler
Exploratory Data Analysis (EDA):
Correlation analysis & feature importance
Data visualizations

Model Development:
Implemented models:
✅ Logistic Regression (97% accuracy)
✅ Support Vector Classifier (SVC) (97% accuracy)
✅ XGBoost (90% accuracy)
✅ Random Forest (87% accuracy)
✅ Decision Tree (82% accuracy)
✅ Naïve Bayes (79% accuracy)
Hyperparameter tuning using GridSearchCV
Model evaluation using accuracy, confusion matrix & ROC-AUC
Deployment & Future Scope:
Real-time model deployment potential
Future improvements: Incorporating brand reputation, customer reviews, and market trends

📊 Key Findings

RAM is the most influential feature in price prediction.
Battery power and screen resolution are strong indicators of price range.
Features like camera resolution and dual SIM capability have minimal impact.

🛠 Tech Stack

Python, pandas, numpy, matplotlib, seaborn
Machine Learning: scikit-learn, XGBoost
Model Evaluation: accuracy_score, confusion_matrix, classification_report

📂 Dataset

📌 Available on Kaggle

🚀 How to Run

Clone the repository
git clone https://github.com/your-repo/mobile-price-prediction.git
cd mobile-price-prediction
Install dependencies
pip install -r requirements.txt
Run the Jupyter Notebook
jupyter notebook

📜 Authors

👨‍💻 Nawaraj Adhikari | 👨‍💻 Patel Manan Champakbhai
📧 Contact: nxa6298@mavs.uta.edu | mxp8783@mavs.uta.edu
