## Summary
This project analyzes COVID-19 death data and aims to develop predictive models to estimate the number of deaths based on various health, demographic, and social factors. 
The dataset includes information on health conditions, age groups, gender, and ethnicity to identify key predictors of COVID-19 death rates. 
The analysis involved data exploration, outlier detection, multivariate analysis, and regression modeling to uncover insights into the factors influencing COVID-19 mortality.

## The main objectives were to:

Analyze the factors affecting COVID-19 death rates across regions.
Develop models to predict deaths based on health conditions, age, sex, and ethnicity.
Identify significant predictors of COVID-19 deaths using regression and factor analysis.
Assess the relative importance of variables in explaining death rates.

## Methodology
The project followed a systematic approach:

Data Preparation: Loading and processing the dataset, including calculating death numbers per 1,000 people.
Exploratory Data Analysis (EDA): Identifying missing values, outliers, and correlations, and visualizing data distributions.
Multivariate Analysis: Analyzing relationships between the dependent and independent variables through scatterplots.
Factor Analysis: Using KMO statistics to check the suitability of factor analysis and assess multicollinearity.
Regression Modeling: Building and simplifying multiple linear regression models, considering multicollinearity using Variance Inflation Factor (VIF).
ANOVA Testing: Comparing model performance to ensure the validity of the regression model simplification.

## Findings
Significant Predictors: Health conditions, age groups, and ethnicity were found to significantly affect COVID-19 death rates. 
Key variables included the percentage of people in good health and the percentage of the population aged 0–29.
Model Performance: The best-performing model (Model 5) included health conditions, age, and ethnicity as predictors.
Multicollinearity: High VIF values for some variables were reduced by model simplification.
Data Insights: Age and health conditions had the most substantial effects on death rates, while sex and ethnicity had a moderate impact.
Relative Importance: The health condition variable, pGood_h, was identified as the most important predictor in the final model.

## Conclusion
This analysis provides important insights into the factors influencing COVID-19 mortality, highlighting health conditions and age as the strongest predictors.
By using regression modeling, significant predictors were identified, which can inform public health strategies and policies.
Further improvements in prediction accuracy could be achieved by exploring other models, such as time-series or machine learning approaches.
