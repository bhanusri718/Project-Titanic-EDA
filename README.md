<img width="960" height="1020" alt="Screenshot 2025-09-15 101032" src="https://github.com/user-attachments/assets/b2e85ae0-8f84-479b-980b-905cda8e5811" />
<img width="960" height="1020" alt="Screenshot 2025-09-15 101017" src="https://github.com/user-attachments/assets/40f47e7b-9291-4c0e-95a5-976fe71bb887" />
<img width="960" height="1020" alt="Screenshot 2025-09-15 101002" src="https://github.com/user-attachments/assets/41f9f5ba-4f32-4e64-b265-2b8b0ff5585c" />
<img width="960" height="1020" alt="Screenshot 2025-09-15 100911" src="https://github.com/user-attachments/assets/3fe0f0d1-da76-4d9f-9d26-493f84bffc03" />
<img width="960" height="1020" alt="Screenshot 2025-09-15 100900" src="https://github.com/user-attachments/assets/2b3c2380-5c18-4552-a80d-b666803a1aa2" />
<img width="960" height="1020" alt="Screenshot 2025-09-15 100849" src="https://github.com/user-attachments/assets/0cd3663f-d150-4c55-96ad-8ced67409f5f" />
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
