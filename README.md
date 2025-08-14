📌 Overview

This repository contains my solution for the Richter's Predictor: Modeling Earthquake Damage hosted on DrivenData.
Out of 2,555 participants, I achieved a leaderboard score of 0.7466, securing Rank 624 (~Top 25%).

The goal of this competition was to predict the level of damage to buildings caused by the 2015 Gorkha earthquake in Nepal based on aspects of building location and construction using the provided dataset.

🛠️ Approach

- Data Exploration & Cleaning

Checked missing values & outliers.
Encoded categorical features.
Normalized/standardized numerical data.

-Modeling

Primary model: XGBoost
Hyperparameter tuning with Optuna.
Evaluated using Stratified K-Fold Cross Validation.

-Improvements

Feature engineering with interaction terms.
Tried ensemble with LightGBM & CatBoost.

| Metric    | Score      |
| --------- | ---------- |
| Public LB | 0.7466     |
| Rank      | 624 / 2555 |

🏆 Leaderboard

📅 Competition Date: 14/08/2025
🏅 Leaderboard Score: 0.7466
📍 Rank: 624 / 2555


