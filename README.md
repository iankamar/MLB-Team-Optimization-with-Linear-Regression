# MLB Team Optimization with Linear Regression

This project builds an optimal MLB team based on predicted player performance using machine learning and optimization techniques.

## Highlights
- Engineered features from historical MLB player stats (BB, HR, singles, doubles, triples)
- Trained and evaluated two models: Random Forest Regressor and Linear Regression
- Linear Regression outperformed and was used for predictions (`R_hat_linear`)
- Applied knapsack optimization to select players under a fixed salary cap
- Explored optimal team drafts without and with position constraints

## Technologies
- Python, Pandas, Scikit-learn, mip (Mixed-Integer Programming), Matplotlib

## Model Evaluation
We evaluated both models using a 67/33 train-test split on `team_features` and `team_runs`.

- **Random Forest Regression** scored: 0.XXX
- **Linear Regression** scored: 0.YYY

## License
Copyright © 2024 Ian Kamar. All rights reserved.
