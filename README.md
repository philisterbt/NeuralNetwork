# NeuralNetwork


This repository contains a machine learning project that predicts the future closing prices of the Borsa Istanbul (BIST 100) index. This work is a reproduction and adaptation of the IEEE conference paper titled "Unlocking Stock Market Potential: Machine Learning Predictions for NIFTY50's Most Profitable Companies".

 Project Overview
The goal of this project is to apply the methodology described in the original paper (which focused on the Indian NIFTY 50 index) to the Turkish Stock Market (BIST 100). The project compares traditional machine learning models with deep learning architectures to determine which approach best suits the dynamics of Borsa Istanbul.

Original Paper: Unlocking Stock Market Potential: Machine Learning Predictions for NIFTY50's Most Profitable Companies

Target Market: BIST 100 (Turkey)

Data Period: Jan 1, 2019 – Jan 1, 2025

🛠 Tech Stack & Libraries
The project is implemented in Python using the following libraries:

Data Source: yfinance

Data Manipulation: pandas, numpy

Technical Analysis: pandas_ta

Machine Learning: scikit-learn (Linear Regression, Decision Tree, Random Forest)

Deep Learning: tensorflow / keras (LSTM)

Visualization: matplotlib

 Methodology
Data Collection: Daily historical data for XU100.IS retrieved via Yahoo Finance.

Feature Engineering: Calculated SMA (10, 50, 200), RSI (14), and MACD as input features.

Preprocessing:

Handling missing values with Linear Interpolation.

Min-Max Scaling (0-1 range).

80% Training / 20% Testing split.

Modeling: Implemented Linear Regression, Decision Tree, Random Forest, and Long Short-Term Memory (LSTM) networks.
