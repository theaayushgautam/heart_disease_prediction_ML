# heart_disease_prediction_ML ❤️📈

**Project Breakdown**

**1. Project Aim**: This project aims to predict the likelihood of heart disease based on various medical indicators, allowing for early detection and prevention. The final product includes a trained machine learning model and a GUI interface where users can input personal health data to receive predictions.

**2. Key Libraries**:

Pandas: Used for data manipulation, loading, and cleaning. Essential for handling large datasets and preprocessing data.

NumPy: Utilized for numerical operations, especially with arrays, and performs essential calculations for machine learning models.

Scikit-Learn:
Model Selection: train_test_split for splitting the dataset into training and testing sets.

Modeling: Various classifiers like LogisticRegression, KNeighborsClassifier, SVM, DecisionTreeClassifier, and RandomForestClassifier were used to experiment with different machine learning algorithms.

Metrics: accuracy_score to evaluate model performance and choose the best model.

Matplotlib & Seaborn: Used for visualization, primarily in the EDA phase to understand the data distribution and identify trends.

Tkinter: A Python library for building the GUI interface, making the model accessible to users without technical expertise.

Joblib: Used to save the trained model, making it easy to deploy and reuse for predictions on new data.

**3. Project Steps:**
**Data Loading & Cleaning**: Import data, handle duplicates, and check for missing values.
**Exploratory Data Analysis**: Visualize data distributions and identify important features influencing heart disease.
**Feature Engineering & Encoding**: Convert categorical variables into numerical values to prepare data for machine learning models.
**Model Training & Evaluation**: Train and compare multiple models (e.g., Logistic Regression, SVM, KNN, Decision Tree, Random Forest) to select the most accurate.
**Building the GUI**: A simple interface that allows users to input their health data and get predictions on heart disease risk.
**Model Deployment**: Save the model using joblib for easy deployment and load it in the GUI for real-time predictions.

This project serves as a practical application of machine learning in healthcare, demonstrating how predictive models can aid in proactive health monitoring.
