# Predicted Goals Model
**Goal :** Using NHL data taken over the last 4 seasons, predict player goal totals using individual and team metrics from the season before such as expected goals, GAR(goals above replacement), shots per game, and high danger shots.
**Skills/Tools :** Python | Excel | sklearn | pandas | machine learning

## Results
Initial random forest model has an RMSE of 6.4 and MAE of 5.1, but will look to tune hyperparmaters through a grid search and find more data to better assess important factors currently not covered such as linemates, share of power play shots, coaching system, and shot quality.

## Repo Map
|      File         |               Purpose               |
|`skaters_22.csv`  | Contains data needed to run the code |
|`skaters_23.csv`  | Contains data needed to run the code |
|`skaters_24.csv`  | Contains data needed to run the code |
|`skaters_25.csv`  | Contains data needed to run the code |
|`pgoals_model.ipynb` |       Contains model code         |
