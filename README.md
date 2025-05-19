# 🐟 Comparative Machine Learning Models for Fish Population Forecasting
This repository presents a comprehensive analysis and implementation of various machine learning and time series models to forecast fish population trends in Maharashtra, India, based on climate change indicators. The goal of this project is to evaluate and compare multiple models to identify the most effective forecasting approach for sustainable fisheries management.
**📌 Table of Contents**
About the Project

Objectives

Dataset Description

Methodology

Models Used

Evaluation Metrics

Results

How to Run

Directory Structure

Visualizations

Conclusion

Future Work

References

**📖 About the Project**
Fish population dynamics are crucial for maintaining ecological balance and supporting the livelihoods of millions. However, climate change poses significant threats to aquatic ecosystems. This project aims to predict total fish landings using historical environmental and fisheries data, leveraging machine learning and time series forecasting techniques.

**🎯 Objectives**
To analyze and clean climate and fishery datasets for Maharashtra.

To develop forecasting models using ML and time series approaches.

To compare the performance of models like ANN, LSTM, Transformer, Random Forest, and SARIMA.

To identify the most suitable model for accurate fish population forecasting.

**🧾 Dataset Description**
Source: Maharashtra Government Fisheries Department & Climate Data Repositories.

Period: Historical records (Year-wise or Month-wise depending on data availability).

Features:

Climate variables: temperature, rainfall, humidity, etc.

Fish population metrics: Total_Fish_Landing_Tonnes.

**🧪 Methodology**
The project was carried out in the following phases:

Data Collection: Aggregated datasets from multiple sources.

Preprocessing:

Removal of duplicates and missing values.

Imputation for incomplete data.

Normalization and encoding where required.

Feature Engineering: Created time-lagged features and handled seasonality.

Model Building:

Split data into training and testing sets.

Trained and tuned multiple models.

Evaluation: Compared models based on MAE, RMSE, MAPE, and R² score.

Visualization: Graphs showing predicted vs actual, error trends, and performance comparison.

**🤖 Models Used**
SARIMA (Seasonal AutoRegressive Integrated Moving Average)
Artificial Neural Network (ANN)
Long Short-Term Memory (LSTM)
Transformer Model
Random Forest Regression
Ensemble Model(ANN+RF)

**📊 Evaluation Metrics**
Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

Mean Absolute Percentage Error (MAPE)

Coefficient of Determination (R² Score)




