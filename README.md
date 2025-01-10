# Travel Insurance Predictive Analysis
![TravelInsurance-ezgif com-resize](https://github.com/user-attachments/assets/98eb68ba-7527-4f80-8b44-477359cfc0b3)

## Description

This notebook analyzes a Kaggle dataset (https://www.kaggle.com/datasets/tejashvi14/travel-insurance-prediction-data) from a Tour & Travel Company that offers a Travel Insurance Package, including Covid coverage, to its customers. The analysis explores customer behavior and identifies key factors influencing the likelihood of purchasing travel insurance, aiding the company in targeting their offers more effectively.

## Objective
The main objective is to identify which customers are more likely to purchase travel insurance. By understanding these patterns, the company can better target its promotional strategies, personalize offers, and increase insurance uptake rates.

## Dataset
For that, the company provided a dataset consisting of the following features:
* **Age:** Age of the customer.
* **Employment Type:** Sector in which the customer is employed.
* **GraduateOrNot:** Whether the customer is college graduate or not.
* **AnnualIncome:** The yearly income of the customer in indian rupees (rounded).
* **FamilyMembers:** Number of members in the customer's family.
* **ChronicDisease:** Whether the customer suffers from any major disease or conditions.
* **FrequentFlyer:** Derived from data based on customer's history of booking air tickets on at least 4 different instances in the last 2 years (2017 - 2019)
* **EverTravelledAbroad:** Whether the customer has ever travelled to a foreign country (not necessarily using the company's services).
* **TravelInsurance:** Whether the customer paid for the travel insurance during the introductory offering held in the year 2019.

## Structure of the notebook
0. Introduction: Brief overview and goals.
1. Loading libraries and dataset: Import necessary libraries and load the dataset.
2. Divide into training and testing sets: Divide the data into training and testing sets for modeling.
3. Descriptive statistics and sanity checks: Generate summary statistics, check for missing values, duplicates, and outliers.
4. Exploratory Data Analysis (EDA): Univariate and multivariate analysis with visualizations.
5. Hypothesis testing: Perform statistical tests to validate assumptions about the data.
6. Modeling: Train and evaluate machine learning models.
7. Conclusions and Improvements: Summarize findings and suggest potential areas for further analysis.

## Results
The analysis identified key factors influencing travel insurance purchases, with features like `Employment Type`, `Frequent Flyer`, and `Annual Income` showing strong correlations with the target variable. Hypothesis testing confirmed significant differences between customer groups, and the final **Logistic Regression** model achieved a recall score of **64%** on the test set. Expanding the dataset and balancing model accuracy with interpretability were recommended for further improvements.
