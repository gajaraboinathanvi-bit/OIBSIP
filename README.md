🌸 Task 1: Iris Flower Classification
Objective: Classify Iris flowers into three species (setosa, versicolor, virginica) based on sepal and petal measurements.

Techniques Used:

Data exploration and pair plots using Seaborn.

Model building using Supervised Machine Learning algorithms (Logistic Regression / Decision Trees / K-Nearest Neighbors).

Evaluation metrics: Accuracy Score, Confusion Matrix, and Classification Report.

Folder Location: DataScience-Task1-IrisFlowerClassification/

📉 Task 2: Unemployment Analysis with Python
Objective: Analyze regional unemployment trends in India and evaluate the socio-economic impact of the COVID-19 pandemic.

Techniques Used:

Data cleaning, whitespace stripping, and datetime parsing.

Exploratory Data Analysis (EDA) with Matplotlib & Seaborn (Bar charts, Time-series plots, and Correlation Heatmaps).

Feature engineering to isolate and compare Pre-COVID vs. Post-COVID periods.

Folder Location: DataScience-Task2-UnemploymentAnalysis/

🔹 Task 3: Car Price Prediction with Machine LearningObjective:

Build a regression model that predicts the selling price of used cars based on specs such as brand, age, mileage, fuel type, and transmission.

Tech Stack: Python, Pandas, Scikit-Learn, Matplotlib, Seaborn.

Key Steps & Features:Cleaned dataset, removed duplicate values, and handled inconsistent categorical data.Engineered new features (extracted Car Age from manufacturing year and Brand from vehicle name).

Encoded categorical variables using One-Hot/Label Encoding and generated correlation heatmaps.

Split data into train/test sets and trained regression models (Linear Regression, Random Forest Regressor, Gradient Boosting).Evaluated models using MAE, RMSE, and $R^2$ Score.

Visualized feature importance for the best-performing model.

# Task 4: Email Spam Detection with Machine Learning

**Oasis Infobyte Data Science Internship (OIBSIP)**

## Project Overview
This project builds a Machine Learning model using Natural Language Processing (NLP) techniques to classify SMS and email messages as either **Spam** or **Ham** (legitimate).

## Key Features
- **Data Preprocessing**: Lowercasing, special character removal, stop-word filtering, and stemming using NLTK `PorterStemmer`.
- **Feature Extraction**: TF-IDF (Term Frequency - Inverse Document Frequency) vectorization.
- **Models Evaluated**:
  - Multinomial Naive Bayes
  - Logistic Regression
- **Evaluation Metrics**: Precision, Recall, Accuracy, F1-Score, and Confusion Matrix.

## Workflow & Steps
1. **Dataset Loading**: Loaded SMS Spam Collection dataset.
2. **Text Cleaning**: Applied regular expressions and stemming to prepare raw text for vectorization.
3. **Exploratory Analysis**: Visualized common spam vs. ham terms using WordClouds.
4. **Model Training**: Split data 80/20 with stratification and evaluated multiple classifiers.

## Performance Summary
- **Multinomial Naive Bayes**: High Precision and F1-score with fast execution time.
- **Logistic Regression**: High baseline accuracy and robust performance on text features.

## Repository Structure
