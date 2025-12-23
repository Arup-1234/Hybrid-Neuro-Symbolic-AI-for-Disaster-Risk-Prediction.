# Hybrid-Neuro-Symbolic-AI-for-Disaster-Risk-Prediction
📌 Project Overview

This project presents a hybrid neuro-symbolic deep learning approach for tropical cyclone intensity prediction using historical cyclone track data. The goal is to improve both prediction accuracy and physical plausibility by combining data-driven neural networks with symbolic domain knowledge.

The project also integrates GIS-based visualization to support spatial risk analysis and interpretability of cyclone behavior across different regions.

🎯 Objectives

Predict short-term tropical cyclone intensity (maximum wind speed)

Combine deep learning with symbolic physical constraints

Compare neural-only and neuro-symbolic models

Visualize cyclone tracks, wind categories, and prediction errors using GIS

🧠 Methodology
Neural Component

Uses a Gated Recurrent Unit (GRU) model

Learns temporal patterns from cyclone sequences

Input features include latitude, longitude, wind speed, and pressure

Symbolic Component

Incorporates soft physical constraints:

Non-negative wind speed

Limited intensity change between time steps

Constraints are added as penalty terms to the loss function

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

Mean Absolute Error (MAE)

Root Mean Square Error (RMSE)

Accuracy within operational tolerance

Spatial error visualization (heatmaps)
📌 Applications

Disaster risk assessment

Early warning systems

Climate research

Emergency planning support

📄 Research Paper Title

Hybrid Neuro-Symbolic Deep Learning for Tropical Cyclone Intensity Prediction and GIS-Based Risk Visualization

👨‍🎓 Author

Student Research Project
Field: Artificial Intelligence & Disaster Risk Prediction
