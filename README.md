# Predicting Life Expectancy using Machine Learning
Here is the problem statement

●	Project Summary

In this project tries to create a new model based on the data provided is to evaluate the life expectancy in  India.The data offers a timeframe from 2015 to 2022. The output algorithms have been used to test if they can maintain their accuracy in predicting the life expectancy for data they haven't been trained. Five algorithms have been used:

1.Linear Regression

2.Polynomial Regression

3.Logistic Regression

4.Ridge Regression

5.Lasso Regression

●	Project Requirements

The scope of this project is to predict the guesstimate given my current knowledge and the limited amount of time I have spent researching and thinking about this question, is that there is a 15% chance that life expectancy will decline in the future. If it does, then my best guess is that the mean value – of the range of possible life expectancies in 2050  is 70 years, which is close to the current value of female life expectancy in the world as a whole. Discussions among a group of experts and systematic consideration of various scenarios would undoubtedly produce values different from 15% and 70 years, but these values illustrate the approach according to the research.
            
●	Functional Requirements
 1. Create a data model present on the database.
 2. The dataset are made available to the public to the purpose of health data  analysis.
3.It is related to the different countries depending on the different countries while finding the dataset in different countries might be difficult and hence we decided that we exclude these countries from the final dataset.

●	Technical Requirements 
1.	The merged dataset by using the databases in the csv formats.
2.	We can use datasets with the help of machine learning and data science with the help of pyhton.
   
●	Software Requirements

Python IDE, Excel, IBM Cloud, IBM Watson 

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

