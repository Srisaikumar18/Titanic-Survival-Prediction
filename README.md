# Titanic Survival Prediction 🚢

## 📌 Project Overview
This project predicts whether a passenger survived the Titanic disaster using machine learning techniques.

## 📊 Dataset
The dataset contains passenger details such as:
- Age
- Gender
- Passenger Class (Pclass)
- Fare
- Embarked location

## ⚙️ Steps Performed
- Data Cleaning (handled missing values)
- Removed irrelevant columns (Name, Ticket, Cabin)
- Encoded categorical variables (Sex, Embarked)
- Data Visualization using Seaborn
- Feature Scaling using StandardScaler
- Model Training and Evaluation

## 🤖 Models Used
- Logistic Regression
- Random Forest Classifier

## 📈 Results
- Logistic Regression Accuracy: ~80%
- Random Forest Accuracy: ~81%

## 🔍 Key Insights
- Female passengers had higher survival rates
- Gender is the most important feature
- Age and Fare also significantly influence survival

## 📊 Visualizations
- Survival Count Plot
- Survival by Gender Plot
- Feature Importance Graph

## 🚀 Future Improvements
- Hyperparameter tuning
- Feature engineering
- Using advanced models like XGBoost

## 🧠 Conclusion
The Random Forest model performed better than Logistic Regression, showing that ensemble models can capture complex patterns in data more effectively.
