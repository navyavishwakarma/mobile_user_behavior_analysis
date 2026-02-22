# Mobile Device Usage & User Behavior Analysis
📖 Project Overview

This project analyzes smartphone usage patterns to understand how device interaction influences user behavior. Using data analysis and machine learning, the project predicts user behavior classes based on mobile usage habits.

🎯 Objective

• Perform data cleaning and preprocessing

• Conduct exploratory data analysis (EDA) to identify trends

• Visualize usage trends and patterns

• Build machine learning models to predict user behavior class

• Compare multiple classification algorithms

🛠 Tools & Libraries Used

• Python

• Pandas & NumPy - data manipulation 
 
• Matplotlib & Seaborn - visualization 

• Scikit-learn - machine learning 

📂 Dataset

Dataset used: Mobile Device Usage and User Behavior Dataset
Source: Kaggle

The dataset includes features such as App Usage Time, Screen On Time, Battery Drain, Number of Apps Installed, Data Usage, Gender, Operating System and User Behavior Class (Target Variable)

📊 Data Cleaning and Preprocessing

The dataset was cleaned and prepared by:

✔ Handling missing values
✔ Encoding categorical variables (Gender, Operating System)
✔ Feature scaling applied to numerical variables
✔ Removing inconsistencies

📈 Exploratory Data Analysis (EDA)

EDA was performed to understand usage patterns and behavioral trends.

Key analysis included:

• Average screen-on time per behavior class

• Battery drain vs usage intensity

• App usage patterns

• Correlation between usage features

📉 Visualizations

The following visualizations were created: 

• Correlation Heatmap

• Scatter Plot (App Usage vs Battery Drain)

• Count Plot of User Behavior Classes

• Distribution plots of usage metrics


🔍 Key Insights

✔ Higher screen on time is strongly linked to heavy usage behavior
✔ Battery drain increases significantly with increased app usage
✔ App usage time is a strong indicator of behavior classification
✔ Moderate users maintain balanced usage patterns
✔ Device usage metrics clearly distinguish user behavior classes

🤖 Machine Learning Models Used

The following classification models were trained and compared:

✔ Logistic Regression

  • Efficient and effective for structured classification tasks

✔ Decision Tree Classifier

  • Captures non-linear patterns and decision rules

✔ K-Nearest Neighbors (KNN)

  • Classifies users based on similarity to neighbors
  
📊 Model Evaluation

Models were evaluated using:

✔ Accuracy Score
✔ Confusion Matrix
✔ Model Comparison

📈 Model Accuracy Comparison

• Logistic Regression: High accuracy

• Decision Tree: Strong performance

• KNN: Reliable results

Logistic Regression achieved the highest accuracy on the test dataset.

🧾 Confusion Matrix

A confusion matrix was generated to visualize prediction performance and classification correctness.

🧠 Conclusion

This project demonstrates that smartphone usage patterns can effectively predict user behavior classes. Machine learning models can analyze user interaction habits to provide insights useful for:

• Digital wellbeing monitoring

• User behavior analytics

• App usage optimization

• UX research

🚀 Future Improvements

• Implement cross-validation

• Hyperparameter tuning

• Build models from scratch using NumPy

• Deploy as a web application

📜 License
This project is created for learning and practice purposes. 
Feel free to fork, modify and improve it.
