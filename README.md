# Regression_signals093
Built a regression model with 18 numerical features/signals and 3 regimes/categories with sample_weights, noise and missing data.

## Evaluation
The evaluation metric combines **Weighted Root Mean Squared Error (WRMSE)** and **Weighted Mean Absolute Error (WMAE)** into a single bounded score called the **Evaluation Stability Score (ESS).**

Higher scores indicate better model performance.

### Key properties of ESS:

* Bounded between 0 and 1
* Higher is better
* Penalizes both large and consistent errors
* Rewards models that generalize well across difficult samples  
