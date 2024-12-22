# Ship Fuel Efficiency and CO2 Emissions Analysis

This project analyzes ship fuel efficiency and CO2 emissions, aiming to optimize routes and predict emissions. The analysis is conducted using advanced machine learning models, time series analysis, and reinforcement learning.

## Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Models and Techniques](#models-and-techniques)
- [Results](#results)
- [Future Work](#future-work)
- [How to Use](#how-to-use)

## Overview
This project focuses on:
1. Optimizing ship routes for fuel efficiency and environmental sustainability.
2. Predicting fuel consumption and CO2 emissions using machine learning models.
3. Recommending optimal routes based on reinforcement learning.

## Objectives
- Improve operational efficiency by analyzing key factors affecting fuel consumption and emissions.
- Develop predictive models for better decision-making.
- Implement route optimization through reinforcement learning.

## Dataset
The dataset includes ship operations data with features such as:
- **Ship ID and Type**
- **Route ID**
- **Distance**
- **Fuel Type**
- **Fuel Consumption**
- **CO2 Emissions**
- **Weather Conditions**
- **Engine Efficiency**

## Methodology
1. **Data Preprocessing:**
   - Handled missing and inconsistent data.
   - Scaled features for machine learning models.
2. **Exploratory Data Analysis:**
   - Analyzed the distribution of routes and ship types.
   - Examined key correlations among features.
3. **Predictive Modeling:**
   - Implemented machine learning models to predict fuel consumption and CO2 emissions.
4. **Reinforcement Learning:**
   - Designed a Q-learning-based system for route recommendations.

## Models and Techniques
- **Machine Learning Models:**
  - Random Forest
  - XGBoost
  - LightGBM
  - Neural Networks
- **Ensemble Learning:**
  - Custom stacking model combining predictions from multiple models.
- **Reinforcement Learning:**
  - Q-learning for route optimization.

## Results
- **Best Model Performance:**
  - Random Forest for fuel consumption prediction: R² = 0.9321
  - Stacked model for CO2 emissions prediction: R² = 0.9937
- **Route Optimization:**
  - Q-learning recommended routes with the highest fuel efficiency and lowest emissions.

## Future Work
- Refine the reinforcement learning model with real-time data updates.
- Expand predictive modeling to include new ship types and routes.
- Integrate weather forecasting for dynamic recommendations.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/shreyashade/ship_efficiency_analysis_modeling_deployment.git

2. Install Requirements
pip install -r requirements.txt

Author
Shreyash Ade
