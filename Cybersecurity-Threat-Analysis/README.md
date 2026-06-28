# 🛡️ Cybersecurity: Suspicious Web Threat Interactions

## Overview
This project focuses on identifying "Critical Anomalies" within already suspicious Web Application Firewall (WAF) logs. Since standard supervised classification models fail due to extreme data leakage (learning to predict 100% "suspicious"), this project utilizes a Deep Learning Autoencoder for unsupervised anomaly detection.

## Key Objectives
1. **Data Loading & Exploration:** Explore WAF threat logs, including network volume and geographical origins.
2. **Feature Engineering & Preprocessing:** Engineer temporal features like connection duration, scale numerical data, and one-hot encode geographic categories.
3. **Deep Learning Autoencoder:** Train a Keras/TensorFlow Autoencoder to compress and reconstruct normal traffic features.
4. **Threat Isolation:** Use Reconstruction Error (Mean Squared Error) to flag the top 10% most extreme deviations as Critical Anomalies, effectively separating standard flagged traffic from highly dangerous anomalies.

## Tech Stack
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, TensorFlow/Keras
- **Modeling:** Deep Learning Autoencoder Neural Network

## Findings
- Eliminated the false 100% accuracy problem from earlier classification attempts.
- Successfully isolated critical threats by establishing an anomaly threshold based on the 90th percentile of reconstruction errors.

