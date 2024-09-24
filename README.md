# Brainwave-Time-Series-Analysis
This repository contains code and analysis for studying the relationship between EEG brainwave activity and design preferences. The project applies time series analysis techniques to explore how various EEG frequencies (Delta, Theta, Beta, Gamma) and gender influence design preferences.

# Overview
 This analysis focuses on identifying significant patterns and relationships in the time series data, using both regression models and interaction analysis.

# Methods Used
- Time Series Analysis: Examining temporal patterns in EEG data.
- Regression Modeling: Assessing relationships between brainwave frequencies (Delta, Theta, Beta, Gamma) and stimuli.
- AIC Model Comparison: Identifying the best-fit model for predicting preferences.
- Visualization: Plotting EEG frequencies and their interactions with stimuli and participant gender.

# Project Setup
- git clone https://github.com/EEG-Time-Series-Analysis.git
- pip install -r requirements.txt
- python eeg_preprocessing.py: Preprocess the EEG time series data.
- python eeg_regression_analysis.py: Run regression models to evaluate the relationships between brainwave activity and preferences.
- python aic_model_comparison.py: Perform AIC-based model comparison.

Tech Stack
Python
- pandas: For data manipulation and preprocessing.
- matplotlib and seaborn: For visualizations.
- statsmodels: For regression analysis.

R ( AIC comparison)
- glm and AIC for advanced model comparison.

# Visualizations
- EEG brainwave activity plotted over time.
- Scatter plots of EEG frequencies vs. design preferences.
- Bar plots of gender-based differences in EEG and preference scores.

# Results
- Model Insights: The interaction between brainwave activity (Delta, Theta, Beta, Gamma) and gender shows significant impact on design preferences.
- AIC Model Comparison: The model with the lowest AIC provides the best fit for predicting preferences based on EEG data.

