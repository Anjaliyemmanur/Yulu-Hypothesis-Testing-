# Yulu-Hypothesis-Testing-

Yulu Demand Analysis 🚲
Project Overview

Yulu is a leading micro-mobility service provider offering shared electric cycles for sustainable urban commuting. This project analyzes the factors affecting the demand for Yulu bikes using Exploratory Data Analysis (EDA) and statistical hypothesis testing.

The objective is to identify the key variables influencing bike rentals and derive actionable business insights to improve operational efficiency and revenue.

Problem Statement

Yulu has experienced a decline in revenue and wants to understand the factors affecting the demand for shared electric cycles in the Indian market.

This analysis focuses on identifying how factors such as:

Season
Weather
Temperature
Working Day
Holiday
Humidity
Windspeed

influence the total number of bike rentals.

Objectives
Perform Exploratory Data Analysis (EDA)
Understand patterns in bike rental demand
Analyze relationships between variables
Conduct statistical hypothesis testing
Generate business insights and recommendations
Dataset Information

The dataset contains information related to:

Date & time
Seasonal conditions
Weather conditions
Temperature
Humidity
Windspeed
Holiday/Working day indicators
Casual and registered users
Total rental count
Target Variable
count

Represents total bike rentals:

count = casual + registered
Concepts Used
Univariate Analysis
Bivariate Analysis
Outlier Detection
Correlation Analysis
Hypothesis Testing
Two Sample T-Test
ANOVA
Chi-Square Test
Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Project Workflow
1. Data Understanding
2. Data Cleaning & Preprocessing
3. Univariate Analysis
4. Bivariate Analysis
5. Correlation Analysis
6. Hypothesis Testing
7. Business Insights
8. Recommendations
Key Insights
Bike rentals are highly influenced by seasonal and weather conditions.
Demand is highest during Summer and Fall.
Clear weather conditions lead to higher rentals, while rainy or misty weather reduces demand.
Comfortable temperatures are associated with increased bike usage.
High humidity and strong windspeed negatively affect rentals.
Working days show slightly higher rental demand due to commuting behavior.
Statistical Tests Performed
1. Two Sample T-Test

Used to check whether working days significantly affect bike rentals.

2. ANOVA

Performed to analyze whether rental counts differ across:

Seasons
Weather conditions
3. Chi-Square Test

Used to determine whether weather conditions are dependent on seasons.

Business Recommendations
Introduce seasonal promotions during low-demand periods.
Use weather forecasting for demand planning.
Optimize bike allocation in high-demand zones.
Improve marketing campaigns targeting commuters.
Build predictive models for future demand forecasting.
Conclusion

The analysis shows that weather and seasonal conditions are the most important drivers of Yulu bike rental demand. Understanding these patterns can help Yulu improve fleet management, pricing strategies, and operational planning to maximize utilization and revenue.
