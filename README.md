Titanic Survival Prediction
Task Objectives
This project aims to predict Titanic passenger survival using Machine Learning. The dataset includes various features like passenger class, age, gender, fare, and embarkation point. The model is built using Random Forest Classifier and optimized with GridSearchCV.
Key Goals:
✅ Preprocess and clean the dataset
✅ Engineer new features for better predictions
✅ Train and evaluate a classification model
✅ Optimize hyperparameters using Grid Search
✅ Save the trained model for future use

 Steps to Run the Project
 git clone https://github.com/your-username/Titanic-Survival-Prediction.git
cd Titanic-Survival-Prediction
 Install Dependencies

 🛠 Technologies Used
Python 
Pandas & NumPy → Data Preprocessing
Matplotlib & Seaborn → Data Visualization
Scikit-Learn → Machine Learning
Joblib → Model Saving

📊 Implementation Details
✅ Data Preprocessing:

Missing values handled using median and mode

Categorical Encoding (Sex, Embarked)

Feature Engineering: Created FamilySize

✅ Feature Scaling:

Used StandardScaler to normalize numerical values

✅ Model Training & Optimization:

RandomForestClassifier for predictions

GridSearchCV for hyperparameter tuning

✅ Model Evaluation:

Accuracy Score

Confusion Matrix

Classification Report

✅ Model Saving:

Trained model saved as titanic_model.pkl
Scaler saved as scaler.pkl
🎯 Evaluation Criteria
✅ Functionality:
The model correctly predicts Titanic passenger survival
✅ Code Quality:
Well-structured and modular Python scripts
✅ Innovation & Creativity:
Feature engineering (FamilySize) improves accuracy
GridSearchCV optimizes performance
✅ Documentation:
README.md clearly explains the implementation
Code Comments make logic easy to understand
