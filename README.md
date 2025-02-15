# Predicting Life Expectancy using Machine Learning

📌 Project Overview

This project aims to predict life expectancy in India using various machine learning regression models. The dataset includes health and socioeconomic factors spanning from 2015 to 2022. The objective is to analyze trends and determine key influencing factors while comparing the performance of different regression techniques.

📂 Dataset

The dataset consists of multiple health and demographic indicators such as:

Economic factors (GDP, health expenditure, income composition)
Health indicators (BMI, immunization rates, mortality rates)
Demographic aspects (population status, schooling, life expectancy)
Environmental factors (pollution levels, sanitation, drinking water access)

📌 Preprocessing Steps:

✔ Handling missing values
✔ Encoding categorical variables
✔ Feature selection and scaling
✔ Outlier detection and removal

The dataset is stored in CSV format for easy access and manipulation.

🔬 Machine Learning Models Used
To predict life expectancy, we experimented with five regression models:

1️⃣ Linear Regression – Basic regression model to understand linear trends
2️⃣ Polynomial Regression – Captures non-linearity in the data
3️⃣ Logistic Regression – Used for categorical classifications within the dataset
4️⃣ Ridge Regression – Helps in reducing overfitting and handles multicollinearity
5️⃣ Lasso Regression – Performs feature selection by penalizing less important features

Each model was trained and evaluated using train-test splits and compared using performance metrics.

📊 Methodology
Exploratory Data Analysis (EDA)

Data visualization using matplotlib and seaborn
Feature correlation analysis
Distribution of key attributes (e.g., GDP, immunization, under-five mortality)
Model Training & Evaluation

Splitting data into training and test sets
Training models using scikit-learn
Evaluating models using:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score (Coefficient of Determination)
Predictions & Analysis

Predicting life expectancy trends
Observing impact of socioeconomic factors
Analyzing changes in feature importance over time
🚀 Results & Findings
🔹 The study suggests a 15% probability of life expectancy decline in the future.
🔹 Estimated mean life expectancy by 2050 is projected to be around 70 years.
🔹 Ridge and Lasso Regression performed best due to their ability to handle multicollinearity.
🔹 GDP, immunization rates, and access to healthcare were among the most influential features.

🔮 Future Enhancements
✅ Expand dataset to include more countries and historical data
✅ Experiment with advanced ML models (Random Forest, Neural Networks)
✅ Conduct time-series analysis for better trend prediction
✅ Integrate additional datasets for a more comprehensive study

⚙ Technical Requirements
🔹 Programming Language: Python
🔹 Libraries Used:

pandas, numpy – Data manipulation
matplotlib, seaborn – Data visualization
scikit-learn – Machine learning models
🔹 Development Environment:
Jupyter Notebook
IBM Watson Studio (for cloud-based computation)

