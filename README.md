# Black Friday Sales Analysis and Prediction

## Project Overview
This project aims to analyze a dataset of Black Friday sales transactions and build a predictive model to forecast purchase amounts. The dataset includes various features such as age, gender, occupation, city category, and stay duration in the current city, along with the purchase details.

## Data Preprocessing
Data preprocessing is a crucial step to ensure the quality of the data before any analysis or modeling. In this project, I handled missing values, encoded categorical variables for model ingestion, and normalized the purchase amounts for better algorithm performance.

## Exploratory Data Analysis
I conducted an extensive EDA to understand the underlying patterns and insights in the data. The EDA includes visualizations of purchase distributions across age groups and gender, comparison of purchase amounts by city category, and an overall distribution of purchase amounts. Furthermore, a heatmap was created to identify correlations between numerical features.

## Customer Segmentation
Using K-Means clustering, I segmented the customers into distinct groups based on their buying behavior and demographic features. This step helped to tailor the marketing strategies for different segments more effectively.

## Predictive Modeling
I built a predictive model using a Gradient Boosting Regressor. The model's hyperparameters were tuned to optimize performance. Cross-validation was used to ensure the model's generalizability and to prevent overfitting.

## Results and Conclusion
The final model showed promising results in predicting purchase amounts. The Mean Squared Error (MSE) metric was used to evaluate the model's performance. Insights drawn from the project can be utilized to drive sales strategies and understand customer behavior better.
