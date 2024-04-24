Hypertension Analysis Project
This project aims to analyze the factors contributing to hypertension (high blood pressure) using data from the 2021 Behavioral Risk Factor Surveillance System (BRFSS) survey conducted by the Centers for Disease Control and Prevention (CDC). The project involves data cleaning, exploratory data analysis, visualization, and building machine learning models to predict the occurrence of hypertension based on various features.

Problem Definitions
What are the variables correlated with the hypertension, and how can we identify undiagnosed individuals suffering hypertension?

Data
The raw dataset is obtained from the 2021 BRFSS survey data, which includes responses from over 400,000 participants in the United States. The original data file can be accessed at: https://www.cdc.gov/brfss/annual_data/annual_2021.html

Contents
• Data Cleaning: Notebook containing the code for data cleaning and preparation.
Data cleaning and preparation are crucial steps in the data analysis process. These steps involve transforming raw data into a format that is suitable for analysis, and ensuring that the data is accurate, complete, and consistent.

• Exploratory Data Analysis and Visualization
Exploratory Data Analysis (EDA) and visualization techniques were applied to gain insights and identify patterns and relationships within the dataset. This helped in understanding the data structure, generating hypotheses, and selecting appropriate models for subsequent analysis.

• Model: Decision Tree
The decision tree model was trained and optimized using the cleaned dataset. The model's performance was evaluated based on key metrics such as true positive rate, false positive rate, and accuracy. The results indicate the model's ability to predict the outcome correctly for a significant portion of the cases.

• Random Forest
The Random Forest model was trained and tuned using the cleaned dataset. The hyperparameters, such as the number of trees and maximum depth, were optimized to achieve the best performance. The model's accuracy, precision, recall, and F1-score were evaluated to assess its predictive capabilities.

• Logistic Regression
The Logistic Regression model was trained using the cleaned dataset, and the coefficient values were estimated for each input variable. These coefficients provide insights into the influence of each feature on the probability of hypertension. Model evaluation was performed using metrics such as accuracy and precision.

Contributions for the project were divided among team members as follows:

Stephanie Heather Zaw: Developed the Random Forest analysis module.
Lee Jia Rong: Created the Decision Tree analysis module.
Yeo Jie Sheng: Implemented the Logistic Regression analysis module.

The team collaborated on Data Cleaning, Exploratory Data Analysis, and Visualization tasks.
