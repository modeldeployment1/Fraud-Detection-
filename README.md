# Fraud-Detection-

A machine learning project focused on detecting fraudulent credit card transactions
Project Overview
This project is focused on detecting fraudulent credit card transactions using machine learning models. Fraud detection is crucial for protecting customers and businesses from unauthorized transactions. In this project, I used various classification models to predict whether a credit card transaction is legitimate or fraudulent based on historical data.
The dataset contains two days of credit card transactions by European cardholders, with a small percentage of fraudulent transactions (0.172%). Due to the imbalance in the dataset, we employed special techniques to ensure accurate fraud detection.
________________________________________
How It Works
1.	Data Loading: We load a dataset of over 284,000 transactions, each labeled as legitimate or fraudulent.
2.	Exploratory Data Analysis (EDA): Basic analysis is performed to understand the structure of the data, identify missing values, and analyze patterns in fraud versus legitimate transactions.
3.	Data Cleaning: Missing values and outliers are handled (though the dataset we use is clean).
4.	Dealing with Imbalanced Data: Since fraud cases are rare, I used oversampling (SMOTE), with oversampling ultimately balancing the dataset effectively.
5.	Feature Engineering: We transform certain features, like scaling the transaction amount, to make them suitable for machine learning models.
6.	Time-based Feature Engineering: Extracting more meaningful time features (e.g., time of day) might improve detection accuracy.
7.	Model Training: 
o	Random Forest
8.	Model Evaluation: Model is evaluated based on accuracy, precision, recall, and F1-score to ensure a balance between catching frauds and minimizing false positives.
9.	Random Forest Model: After testing, Random Forest was found to be the most accurate and reliable model for this project.
________________________________________
Technologies Used
1.	Python: The programming language used for building and training the models.
2.	Pandas & NumPy: For data manipulation and analysis.
3.	scikit-learn: A powerful library for machine learning, used for model building and evaluation.
4.	Jupyter Notebook: Used for coding and testing the project.
5.	Deployment: Streamlit App and Stream Cloud
________________________________________
How to Run the Project
1.	Download the dataset: The dataset is available in this repository.
2.	Install the Required Libraries:
o	The key libraries required are pandas, numpy, scikit-learn, and imbalanced-learn.
3.	Run the Code: After installing the dependencies, run the Python script: -This will train the models, evaluate them, and print the performance metrics (accuracy, precision, recall, F1-score).
________________________________________
Results
•	The Random Forest model achieved the best results with:
o	Accuracy: 100%
o	Precision: 100%, meaning very few false fraud flags
o	Recall:  100%, meaning it catches almost all frauds
o	F1-Score: Almost perfect, indicating a balanced performance
________________________________________
Future Improvements
1.	Hyperparameter Tuning: Further improvements can be made by tuning the parameters of the Random Forest or other models.
2.	Real-time Prediction: Integrating the model into an API for real-time fraud detection.
________________________________________
Conclusion
This project demonstrates how machine learning can be used to effectively detect credit card fraud. By using models like Random Forest and techniques to handle imbalanced data, we achieved high accuracy and reliability in predicting fraudulent transactions.

