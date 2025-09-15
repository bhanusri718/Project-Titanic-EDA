# Titanic Dataset Analysis

This repository contains an exploratory data analysis (EDA) of the Titanic dataset using **Seaborn** and **Matplotlib**.

## Dataset
The Titanic dataset provides details of passengers such as:
- Passenger class (Pclass)
- Sex
- Age
- Fare
- Survival status (0 = Did not survive, 1 = Survived)

This dataset is widely used for data analysis and machine learning practice.

## Analysis Steps
1. Loaded the Titanic dataset into a pandas DataFrame.
2. Performed exploratory analysis on the following features:
   - Survival by passenger class and gender
   - Age distribution of survivors vs non-survivors
   - Fare distribution across classes
   - Correlation between numeric variables
3. Visualizations were generated using Seaborn and Matplotlib.

## Key Insights
- **Gender impact**: Females had a much higher survival rate than males across all classes.
- **Class influence**: First-class passengers had higher survival probabilities compared to second- and third-class passengers.
- **Age factor**: Younger passengers had a slightly higher chance of survival; however, the relationship was not linear.
- **Fare**: Higher fares were associated with higher survival rates, strongly linked to passenger class.
- **Correlations**: Passenger class and fare showed strong associations with survival.

## Repository Structure
