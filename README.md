# Wine Classification with PCA and k-NN

This project uses PCA and GridSearchCV-optimized k-Nearest Neighbors for classifying wines from the UCI Wine dataset.

## Highlights
- Performed exploratory data analysis (EDA) and data visualization
- Applied Principal Component Analysis (PCA) for dimensionality reduction
- Tuned k-NN hyperparameters using GridSearchCV
- Achieved 96% classification accuracy
- Visualized clusters and confusion matrix

## Technologies
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, GridSearchCV

## Dataset
This project uses the UCI Wine dataset for classification.

---

## MLB Team Optimization with Linear Regression

This project builds an optimal MLB team based on predicted player performance using machine learning and optimization techniques.

### Highlights
- Engineered features from historical MLB player stats (BB, HR, singles, doubles, triples)
- Trained and evaluated two models: Random Forest Regressor and Linear Regression
- Linear Regression outperformed and was used for predictions (`R_hat_linear`)
- Applied knapsack optimization to select players under a fixed salary cap
- Explored optimal team drafts without and with position constraints

### Technologies
Python, Pandas, Scikit-learn, mip (Mixed-Integer Programming), Matplotlib

### Model Evaluation
We evaluated both models using a 67/33 train-test split on `team_features` and `team_runs`.

```python
Random Forest Regression scored: 0.XXX
Linear Regression scored: 0.YYY
