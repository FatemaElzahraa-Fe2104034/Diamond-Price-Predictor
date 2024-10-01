# CMPS 460 Project Repository
# Diamond Price Prediction Project

## Project Overview
This project aims to develop machine learning models that accurately predict diamond prices based on various attributes such as carat, cut, color, clarity, and more. Given the significant economic and cultural value that diamonds hold, accurately predicting their prices is a valuable task for both industry professionals and consumers.

## Objectives
1. **Prediction Accuracy**: 
   - Develop machine learning models to predict diamond prices with high precision. The goal is to preprocess the data, remove noise, and train models to identify the most effective predictors.
   
2. **Model Evaluation**: 
   - Evaluate model performance using appropriate metrics like Mean Squared Error (MSE). This helps in identifying the best-performing models and fine-tuning them for better results.

3. **Feature Importance Analysis**: 
   - Understand the impact of each feature on diamond price predictions. This provides insights into the key factors influencing diamond prices, which can be beneficial for stakeholders and domain experts.

## Dataset
The dataset used in this project contains prices and other attributes for nearly 54,000 diamonds. The attributes include:
- **Carat**: The weight of the diamond.
- **Cut**: Quality of the cut (e.g., Fair, Good, Very Good, Premium, Ideal).
- **Color**: Color grading from J (worst) to D (best).
- **Clarity**: The level of inclusions or blemishes, ranging from I1 (worst) to IF (best).
- **Depth**: The total depth percentage, calculated as 2 * z / (x + y), where x and y are the diamond's width and z is the height.

## Installation
To run this project locally, you'll need to install the following dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn torch
