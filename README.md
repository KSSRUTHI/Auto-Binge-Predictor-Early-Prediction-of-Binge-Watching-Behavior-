# Auto-Binge Predictor 

A machine learning-based system for early prediction of binge-watching behavior using initial user interaction data. This project leverages behavioral features and explainable AI to model binge likelihood in real-time.

## Overview

This work introduces a predictive pipeline that identifies binge-watching tendencies using first-session features such as watch duration percentage, pause/skip behavior, device type, mood, and session continuity. Unlike traditional models that rely on long-term viewing history, this framework makes accurate predictions from early interaction footprints.

## Features

-  Structured behavioral data processing
-  Feature engineering (e.g., attention spikes, momentum)
-  Multi-model comparison:
  - XGBoost (Best: 95.65% accuracy)
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Dummy Classifier (Baseline)
- Performance evaluation: Accuracy, Precision, Recall, F1-score
-  SHAP explainability for feature impact insights

## Technologies Used

- Python 3.11+
- Scikit-learn
- XGBoost
- SHAP
- Pandas, NumPy, Seaborn, Matplotlib

## Usage

1. **Clone the repository**  
   ```bash
   https://github.com/KSSRUTHI/Auto-Binge-Predictor-Early-Prediction-of-Binge-Watching-Behavior-.git
   cd auto-binge-predictor
