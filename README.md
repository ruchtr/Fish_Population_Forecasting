# 🐟 Comparative Machine Learning Models for Fish Population Forecasting
This repository presents a comprehensive analysis and implementation of various machine learning and time series models to forecast fish population trends in Maharashtra, India, based on climate change indicators. The goal of this project is to evaluate and compare multiple models to identify the most effective forecasting approach for sustainable fisheries management.

# 📖 About the Project
Fish population dynamics are crucial for maintaining ecological balance and supporting the livelihoods of millions. However, climate change poses significant threats to aquatic ecosystems. This project aims to predict total fish landings using historical environmental and fisheries data, leveraging machine learning and time series forecasting techniques.

# 🎯 Objectives
To analyze and clean climate and fishery datasets for Maharashtra.

To develop forecasting models using ML and time series approaches.

To compare the performance of models like ANN, LSTM, Transformer, Random Forest, and SARIMA.

To identify the most suitable model for accurate fish population forecasting.

# 🧾 Dataset Description
Source: Maharashtra Government Fisheries Department & Climate Data Repositories.

Period: Historical records (Year-wise or Month-wise depending on data availability).

Features:

Climate variables: temperature, rainfall, humidity, etc.

Fish population metrics: Total_Fish_Landing_Tonnes.

# 🧪 Methodology
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

# 🤖 Models Used
SARIMA (Seasonal AutoRegressive Integrated Moving Average)
Artificial Neural Network (ANN)
Long Short-Term Memory (LSTM)
Transformer Model
Random Forest Regression
Ensemble Model(ANN+RF)

# 📊 Evaluation Metrics
Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

Mean Absolute Percentage Error (MAPE)

Coefficient of Determination (R² Score)

# ✅ Conclusion
he primary objective of this project was to forecast fish landings in Maharashtra using 
climate change-related environmental data through a comparative analysis of various 
machine learning and time series models. Among the five models trained and evaluated, 
Random Forest, Transformer, and an Ensemble model (ANN + RF) emerged as the top 
performers. 

The Random Forest model was found to capture general trends effectively but showed 
limitations in representing sharp peaks and sudden drops in fish landing volumes due to its 
averaging mechanism. Its predictions were more stable but less responsive to extreme 
variations in the data. 

The Transformer model demonstrated a stronger ability to track both long- and short-term 
fluctuations, thanks to its attention mechanism. It adapted well to complex variations and 
outperformed Random Forest in regions with high variance. However, occasional 
mismatches were observed where it either overshot or undershot extreme values. 

The Ensemble model, combining the strengths of Random Forest and ANN, showed the 
most robust and reliable performance. It successfully learned from both non-linear patterns 
and feature interactions, demonstrating better generalization and precision across various 
sample points. The visualizations clearly supported its superior predictive ability, especially 
for real-world fishery forecasting tasks. 

Overall, the comparative evaluation revealed that hybrid and deep learning models hold 
substantial promise for climate-driven fish population forecasting. The ensemble approach, 
in particular, is well-suited for applications in fisheries resource planning and management.




