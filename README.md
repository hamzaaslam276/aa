🩺 Diabetes Health Indicators Analysis
This repository contains an exploratory data analysis (EDA) of diabetes-related health indicators from the 2015 Behavioral Risk Factor Surveillance System (BRFSS) dataset. The goal is to uncover patterns and relationships between diabetes and other health metrics such as BMI, blood pressure, cholesterol, age, and lifestyle factors.

📁 Datasets Used
Three datasets were used and merged for comprehensive analysis:

diabetes_012_health_indicators_BRFSS2015.csv

diabetes_binary_5050split_health_indicators_BRFSS2015.csv

diabetes_binary_health_indicators_BRFSS2015.csv

🧹 Data Preprocessing
Loaded all three datasets using pandas.

Concatenated them into one master DataFrame.

Reset index and handled duplicated index entries.

Identified and dropped rows with null values (especially from the Diabetes_012 column).

Verified data integrity post-cleaning.

📊 Exploratory Data Analysis (EDA)
Visualizations were created using Seaborn and Matplotlib to understand:

Diabetes Class Distribution
Count of individuals with and without diabetes.

Diabetes Prevalence by Age Group
How diabetes frequency varies across different age brackets.

Diabetes and High Blood Pressure
Comparison of diabetes rates among those with and without high blood pressure.

Diabetes and BMI
A boxplot showcasing BMI variation between diabetic and non-diabetic individuals.

📌 Key Visualizations

Visualization	Description
countplot	Class distribution of diabetes presence
barplot	Average diabetes prevalence by age
countplot (hue)	Diabetes vs. HighBP cross-distribution
boxplot	BMI spread among diabetic vs. non-diabetic individuals
📦 Dependencies
Make sure to install the following Python libraries before running the code:

bash
Copy
Edit
pip install pandas numpy seaborn matplotlib
▶️ How to Run
Clone this repository

Place the three CSV files in the working directory

Run the Python script or Jupyter Notebook to generate visualizations

✅ Future Enhancements
Apply machine learning models for diabetes prediction

Feature selection and correlation analysis

Deploy insights via an interactive dashboard (Streamlit or Power BI)

