# car-price-prediction
🚗 Ford Car Price Prediction Using Linear Regression

📌 Project Overview

This project focuses on predicting Ford car prices using Machine Learning, with Linear Regression as the primary algorithm.

The main objective is to understand how different categorical encoding techniques affect model performance. To explore this, I built two Linear Regression models using One-Hot Encoding and Label Encoding, respectively, and compared their R² scores.

🎯 Objectives

- Understand and implement Linear Regression.
- Prepare categorical features for machine learning.
- Apply One-Hot Encoding and Label Encoding.
- Train two separate Linear Regression models.
- Generate predictions and compare model performance.
- Evaluate the models using the R² score.

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Matplotlib / Seaborn (if used in the notebook)

📊 Project Workflow

1. Load the Ford car dataset.
2. Explore the dataset and prepare the features.
3. Separate the input features ("X") and target variable ("y").
4. Apply One-Hot Encoding to categorical features for the first model.
5. Apply Label Encoding to categorical features for the second model.
6. Split the data into training and testing sets.
7. Train both Linear Regression models.
8. Generate predictions using the test data.
9. Compare the models using their R² scores.

🤖 Models Implemented

1. Linear Regression with One-Hot Encoding

In the first model, categorical features are converted into binary indicator columns using One-Hot Encoding.

R² Score: 83%

2. Linear Regression with Label Encoding

In the second model, categorical values are converted into numerical labels using Label Encoding.

R² Score: 73%

📈 Model Performance Comparison

Model| Encoding Technique| R² Score
Model 1| One-Hot Encoding| 83%
Model 2| Label Encoding| 73%

Observation

In this experiment, the Linear Regression model using One-Hot Encoding achieved an R² score that was 10 percentage points higher than the model using Label Encoding.

One possible explanation is that Label Encoding assigns numerical labels to categories, which can introduce an artificial numerical relationship between categories. One-Hot Encoding represents categories separately instead.

The results depend on the dataset, selected features, preprocessing steps, and model configuration.

Note: The R² score is not the same as prediction accuracy. An R² score of 0.83 means the model explains approximately 83% of the variance in the target values on the evaluated data.

💡 Key Learnings

- Understanding the practical implementation of Linear Regression.
- Learning the difference between One-Hot Encoding and Label Encoding.
- Observing how preprocessing choices can influence model performance.
- Training and testing machine learning models using Scikit-learn.
- Generating predictions and comparing actual versus predicted values.
- Evaluating regression models using the R² score.

🚀 Future Improvements

- Evaluate both models using MAE and RMSE.
- Perform additional data cleaning and feature analysis.
- Experiment with other regression algorithms.
- Tune model parameters and compare results.
- Evaluate the models on consistent train-test splits and preprocessing pipelines.

👨‍💻 Author

Vishnu Mishra

B.Tech Student | Aspiring Data Analyst | Machine Learning Learner

---

This project was developed as part of my practical learning journey in Python, Data Analytics, and Machine Learning.
