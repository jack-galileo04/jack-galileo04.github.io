# EPL Match Prediction Model

### Tools: R, tidymodels, tidyverse, xgboost  
### Problem: Predict EPL match outcomes (H/D/A)  
### Metric: Multinomial Log Loss  
### Best result: 0.89

## Overview
This project builds a predictive model using:
- rolling averages
- Advanced features (xG, xA, XGChain...)
- bookmaker odds comparison
- home/away team stats
- ELO
- differential features
- model tuning with tidymodels

## Repository Structure
/ data/ raw processed/ scripts/ cleaning.R feature_engineering.R modelling.R evaluation.R/

## Results
- Best log loss: 0.89  
- Upon testing various ML models, XGBoost performed the best.
- Differential features improved stability

## Future Improvements
- Testing neural networks
- Testing stacking and isotonic regression calibration
- Improving ingestion and deployment
