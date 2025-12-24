# Hybrid-Neuro-Symbolic-AI-for-Disaster-Risk-Prediction
📌 Project Overview

This project presents a hybrid neuro-symbolic deep learning approach for tropical cyclone intensity prediction using historical cyclone track data. The goal is to improve both prediction accuracy and physical plausibility by combining data-driven neural networks with symbolic domain knowledge.

The project also integrates GIS-based visualization to support spatial risk analysis and interpretability of cyclone behavior across different regions.

🎯 Objectives

1. Predict short-term tropical cyclone intensity (maximum wind speed)

2. Combine deep learning with symbolic physical constraints

3. Compare neural-only and neuro-symbolic models

4. Visualize cyclone tracks, wind categories, and prediction errors using GIS

🧠 Methodology
 Neural Component

1. Uses a Gated Recurrent Unit (GRU) model

2. Learns temporal patterns from cyclone sequences

3. Input features include latitude, longitude, wind speed, and pressure

Symbolic Component

1. Incorporates soft physical constraints:

2. Non-negative wind speed

3. Limited intensity change between time steps

4. Constraints are added as penalty terms to the loss function

🗂 Dataset

NOAA HURDAT2 Tropical Cyclone Dataset

Covers Atlantic and Pacific basins

Source: Kaggle (NOAA Hurricane Database)

🗺 GIS Visualization

The project includes GIS-based analysis to:

Map cyclone tracks

Classify wind intensity (TD, TS, C1, C2, etc.)

Generate regional maps (Atlantic, Pacific, Caribbean)

Create error heatmaps showing spatial model uncertainty

📊 Evaluation Metrics

1. Mean Absolute Error (MAE)

2. Root Mean Square Error (RMSE)

3. Accuracy within operational tolerance

4. Spatial error visualization (heatmaps)

📌 Applications

1. Disaster risk assessment

2. Early warning systems

3. Climate research

4. Emergency planning support

 Title

Hybrid Neuro-Symbolic Deep Learning for Tropical Cyclone Intensity Prediction and GIS-Based Risk Visualization

👨‍🎓 Author

Student Research Project
Field: Artificial Intelligence & Disaster Risk Prediction
