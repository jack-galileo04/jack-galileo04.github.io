# NRL Match Prediction Model

### Tools: R, tidymodels, tidyverse, xgboost, lasso-regression, random forests, stacking  
### Problem: Predict EPL match outcomes (H/A)  
### Metric: Multinomial Log Loss
### Best result: x

## Overview
This project builds a predictive model using:
- rolling averages
- bookmaker odds comparison
- home/away team stats
- differential features
- model tuning with tidymodels

## Repository Structure
/ data/ raw processed/ scripts/ cleaning.R feature_engineering.R modelling.R evaluation.R

## Results
- Best log loss: x
- Bookmaker odds and tuned ELO were the strongest predictors

## Future Improvements
- Rely less on strongly predictive bookmaker odds
- Use more granular data
- Optimise ingestion and deployment processes
