# NRL Match Prediction Model

### Tools: R, tidymodels, tidyverse, xgboost, lasso-regression, random forests, stacking  
### Problem: Predict EPL match outcomes (H/A)  
### Metric: Multinomial Log Loss
### Best result: Log Loss of 0.55 (binary classification)

## Overview
This project builds a predictive model using:
- rolling averages
- bookmaker odds comparison
- home/away team stats
- differential features
- model tuning with tidymodels

## Data
Data is sourced from https://www.aussportsbetting.com/data/historical-nrl-results-and-odds-data/

## Repository Structure
/ data/ raw/ nrl.xlsx / processed/clean_matches.csv feature_engineered.csv / scripts/ helper_functions_packages.R cleaning_script.R feature_engineering_script.R modelling_script.R evaluation_script.R

## Results
- Best log loss: x
- Bookmaker odds and tuned ELO were the strongest predictors

## Future Improvements
- Rely less on strongly predictive bookmaker odds
- Use more granular data
- Optimise ingestion and deployment processes
