# 📊 Oasis Infobyte Data Science Internship (OIBSIP)

This repository contains all the completed tasks for the **Data Science Internship** at **Oasis Infobyte**. The projects demonstrate a end-to-end data science lifecycle, including exploratory data analysis (EDA), data cleaning, text preprocessing, feature engineering, and supervised machine learning model development.

---

## 📂 Project Repository Structure

```text
├── Task 1 - Iris Flower Classification/
│   ├── Iris_Flower_Classification.ipynb
│   └── Iris.csv
├── Task 2 - Unemployment Analysis with Python/
│   ├── Unemployment_Analysis.ipynb
│   └── Unemployment_Rate_upto_11_2020.csv
├── Task 3 - Car Price Prediction with Machine Learning/
│   ├── Car_Price_Prediction.ipynb
│   └── car_data.csv
├── Task 4 - Email Spam Detection with Machine Learning/
│   ├── Email_Spam_Detection.ipynb
│   └── spam.csv
└── README.md
📌 Task Summary🌸 Task 1: Iris Flower ClassificationObjective: Build a machine learning classification model to accurately predict the species of an Iris flower based on physical measurements (sepal length, sepal width, petal length, and petal width).Key Steps:Performed Exploratory Data Analysis (EDA) using pair plots and correlation heatmaps.Encoded categorical targets (Setosa, Versicolor, Virginica).Split data into training and testing sets.Evaluated algorithms: Support Vector Machine (SVM) and Logistic Regression.Result: Achieved ~98%-100% accuracy on test data classification.
📈 Task 2: Unemployment Analysis with PythonObjective: Analyze labor market trends and visualize the impacts of economic factors on the unemployment rate in India across different regions and timeframes (including COVID-19 lockdown impact).Key Steps:Handled data formatting and date-time parsing for regional datasets.Extracted temporal metrics (month, year) and geographic features.Generated insightful charts: Bar charts, Box plots, Regional Heatmaps, and Time Series line plots comparing Unemployment Rate vs. Estimated Employed Population.Key Insight: Identified significant spikes in unemployment across specific states during lockdown periods (March–May 2020).
🚗 Task 3: Car Price Prediction with Machine LearningObjective: Build a predictive regression model to estimate the selling prices of used cars based on historical attributes.Key Steps:Preprocessed categorical variables (e.g., Fuel Type, Seller Type, Transmission) using One-Hot and Label Encoding.Feature scaling and correlation matrix assessment to identify key price drivers (Vehicle Age, Driven KMS, Present Price).Evaluated algorithms: Linear Regression, Random Forest Regressor, and XGBoost.Result: Random Forest/XGBoost achieved an $R^2$ score > 0.90, outperforming linear models.
📩 Task 4: Email & SMS Spam DetectionObjective: Construct a Natural Language Processing (NLP) text classification pipeline to detect whether a message is Spam or Ham (legitimate).Key Steps:Cleaned text by stripping special characters, lowercasing, and removing English stopwords.Applied PorterStemmer for text normalization.Visualized key text frequencies using WordCloud (side-by-side SPAM vs. HAM visual analysis).Vectorized preprocessed text into numerical representations using TF-IDF Vectorization.Trained and evaluated Multinomial Naive Bayes and Logistic Regression classifiers.Result: Achieved ~97.5% classification accuracy with high precision on unseen test messages.🛠️ Tools & Technologies UsedProgramming Language: Python 3.xData Processing: pandas, numpyData Visualization: matplotlib, seaborn, wordcloud, plotlyMachine Learning & NLP: scikit-learn, nltkDevelopment Environment: Google Colab / Jupyter Notebook


