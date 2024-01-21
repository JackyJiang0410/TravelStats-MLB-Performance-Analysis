# Travel Stats: Effects of Travel on Team Performance

## Project Overview
This project analyzes the impact of travel schedules on the performance of Major League Baseball (MLB) teams. It aims to determine if factors such as travel distance, consecutive road games, and rest days significantly affect game outcomes.

## Data Source
The dataset comprises 56,775 entries from MLB games, including game dates, team details, venue information, scores, and performance statistics.

## Data Processing
### Feature Engineering: 
Added geographical coordinates, calculated travel distances and times, and created interaction terms like travel distance differences.
### Data Wrangling: 
Employed OneHotEncoder, StandardScaler, and ColumnTransformer for data preparation.

## Model Selection and Analysis
### Model: 
eXtreme Gradient Boosting (XGBoost), selected for its effectiveness in handling tabular data.
### Tuning: 
RandomizedSearchCV was used for hyperparameter optimization.
### Results: 
The model achieved 89.9% accuracy in cross-validation.
### Feature Importance: 
Analysis of in-game stats and travel features was conducted.

## Results
### Travel Impact: 
Travel was found to be a significant, though not dominant, factor in team performance.
### Visualization: 
Partial Dependence Plots illustrated the relationship between travel distances and win probability.

## Usage
Run the Jupyter notebook JackyJiang_RiceDatathon24.ipynb to start the analysis.
Follow the step-by-step instructions in the notebook to replicate or extend the analysis.
