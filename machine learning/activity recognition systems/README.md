🌟 Introduction
This project analyzes smartwatch data to classify user activities like Lying, Walking, and Running. Smartwatches collect data on various parameters such as heart rate, steps, calories burned, and more. Using this data, we aim to predict user activity accurately.

📂 Dataset Overview
Source: Proprietary dataset
Total Entries: 6,264
Features: 19 (including target variable activity)
Target Variable: activity (Categorical: Lying, Walking, Running)

Dataset Sample
X1	Age	Gender	Height	Weight	Steps	Heart Rate	Calories	Distance	Device	Activity
1	20	Male	168 cm	65.4 kg	10.77	78.53	0.34	0.008	Apple Watch	Lying
2	20	Male	168 cm	65.4 kg	11.47	78.45	3.28	0.009	Apple Watch	Lying

🎯 Problem Statement
Is this Supervised or Unsupervised Learning?
This is a Supervised Learning problem because we have labeled data (activity).

Regression or Classification?
This is a Classification Problem, where we predict the target variable (activity) from three categories:

Lying
Walking
Running

🔍 Data Quality Assessment
Data Shape and Structure
Rows: 6,264
Columns: 19
Data Types
Feature	Data Type
age	Integer
height	Float
activity	Object
Missing Data
No missing values were detected in the dataset. All 19 columns have complete entries.

Descriptive Statistics
Feature	Mean	Std Dev	Min	Max
Steps	109.56	222.79	1	2,759
Heart Rate	86.14	28.64	2.22	3,000

📊 Exploratory Data Analysis (EDA)
Correlation Analysis: Examined relationships between heart rate, steps, and activity level.
Data Distribution: Visualized the distribution of steps and heart rate using histograms.
Outlier Detection: Checked for anomalies in features like calories and distance.

🤖 Machine Learning Model
Approach: Classification
Target Variable: activity
Algorithms Explored:
Random Forest Classifier

Also we can use Support Vector Machine (SVM),Decision Tree Classifier models.

📈 Key Results
Achieved high accuracy in predicting activities using optimized machine learning models.
Created a confusion matrix to analyze misclassifications.
F1-score validated the model's reliability for activity recognition tasks.

🔧 Tools & Technologies Used
Languages: Python
Libraries: pandas, numpy, matplotlib, seaborn, sklearn
Algorithms: Supervised Classification (Random Forest)
Environment: Jupyter Notebook