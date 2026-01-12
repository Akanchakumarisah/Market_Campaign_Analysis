# Market_Campaign_Analysis
📊 Market Campaign Analysis (R Language)

🧠 Overview
The Market Campaign Analysis project focuses on understanding customer behavior, identifying key factors influencing campaign success, and providing actionable insights for marketing strategy improvement.
Using R language, the project performs data cleaning, exploratory data analysis (EDA), and predictive modeling to evaluate the performance of a marketing campaign dataset.


🎯 Objectives
Analyze customer demographics and behavior patterns.
Identify factors influencing the success of marketing campaigns.
Visualize relationships between customer attributes and response rates.
Build predictive models to estimate campaign effectiveness.


🧰 Tools & Technologies
Category	Tools Used
Programming Language	R
Libraries	tidyverse, dplyr, ggplot2, readr, caret, corrplot, randomForest
IDE	RStudio
Visualization	ggplot2, corrplot
Dataset Handling	CSV file (Marketing Campaign Data)


📁 Project Structure
Market_Campaign_Analysis/
│
├── data/
│   └── marketing_campaign.csv        # Dataset used for analysis
│
├── scripts/
│   ├── data_cleaning.R               # Handles missing values and data preprocessing
│   ├── eda_visualization.R           # Performs EDA and visualization
│   ├── model_building.R              # Builds predictive models
│
├── results/
│   ├── correlation_matrix.png        # Correlation heatmap
│   ├── feature_importance.png        # Top influencing features
│   └── model_accuracy.txt            # Model performance summary
│
└── README.md                         # Project documentation


🧹 Data Preprocessing
Handled missing values and duplicates.
Converted categorical variables into factors.
Scaled numerical attributes for better model performance.
Removed outliers using IQR method.


📈 Exploratory Data Analysis (EDA)
Analyzed age, income, spending score, and campaign responses.
Created histograms, boxplots, and correlation heatmaps.
Discovered key insights such as:
Customers with mid-to-high income respond more positively.
Married customers and those with children have lower engagement rates.
Previous campaign success is strongly correlated with current response rate.



🤖 Predictive Modeling
Built models to predict whether a customer will respond to a marketing campaign.
Models used:
Logistic Regression
Random Forest
Decision Tree

Evaluated using metrics like:
Accuracy
Precision & Recall
F1 Score
ROC-AUC

Best Model: Random Forest with highest accuracy and balanced recall–precision performance.


📊 Key Visualizations
Customer distribution by age and income
Response rate across marital status and education
Correlation heatmap between numeric variables
Feature importance from Random Forest model

📑 Insights & Recommendations
Focus on mid-income working professionals — they show higher conversion rates.
Personalized campaigns for loyal customers increase success probability.
Reducing over-contact with the same customers prevents negative responses.
Targeted email campaigns outperform mass campaigns.


🚀 How to Run



Open the project in RStudio.

Install required libraries:
install.packages(c("tidyverse", "dplyr", "ggplot2", "corrplot", "caret", "randomForest"))


Run scripts in the following order:

source("scripts/data_cleaning.R")
source("scripts/eda_visualization.R")
source("scripts/model_building.R")

🧾 Results Summary
Model	Accuracy	Precision	Recall	F1 Score
Logistic Regression	0.82	0.79	0.77	0.78
Decision Tree	0.85	0.82	0.81	0.81
Random Forest	0.90	0.88	0.87	0.87


📚 Learning Outcomes
Advanced understanding of data preprocessing and feature engineering in R.
Practical experience with EDA and visualization using ggplot2.
Exposure to predictive modeling and performance evaluation.
Improved ability to derive business insights from data-driven results.

