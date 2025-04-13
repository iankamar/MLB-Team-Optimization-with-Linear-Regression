# MLB Team Optimization with Linear Regression

This project builds an optimal MLB team based on predicted player performance using machine learning and optimization techniques.

## Dataset

The dataset used for this project is from the **Baseball Databank** available on [Kaggle](https://www.kaggle.com/datasets/danielmontilla/baseball-databank). It contains detailed statistics for MLB players, including batting, pitching, and fielding data. Additional data was sourced from the **Lahman Baseball Database**, specifically the [Appearances.csv](https://github.com/michaeljaltamirano/lahman-baseball-database-2016-postgresql/blob/master/csv/Appearances.csv) file, which contains player appearances and game participation details.

## Highlights
- Engineered features from historical MLB player stats (BB, HR, singles, doubles, triples)
- Trained and evaluated two models: **Random Forest Regressor** and **Linear Regression**
- **Random Forest Regression** outperformed and was used for predictions (`R_hat_linear`)
- Applied **knapsack optimization** to select players under a fixed salary cap
- Explored optimal team drafts without and with position constraints

## Technologies
- Python, Pandas, Scikit-learn, mip (Mixed-Integer Programming), Matplotlib

## Model Evaluation
I evaluated both models using a 67/33 train-test split on `team_features` and `team_runs`.

- **Random Forest Regression** scored: 0.XXX
- **Linear Regression** scored: 0.YYY

## License
Copyright © 2024 Ian Kamar. All rights reserved.
