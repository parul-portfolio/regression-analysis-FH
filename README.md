# regression-analysis-FH
Clinical risk modelling with logistic regression
## Clinical Risk Modeling with Logistic Regression (R)

### Business Problem
Healthcare organizations need reliable risk models to identify patients
at higher risk of adverse clinical events. These models must handle missing
data, avoid overfitting, and be properly validated.

### Objective
To develop and validate a logistic regression–based risk model using
clinical and laboratory variables.

### Methods
- Exploratory data analysis
- Multiple imputation for missing data
- Univariable and multivariable logistic regression
- Feature selection using AIC and stepwise methods
- Bootstrapping to assess model stability
- Calibration and performance evaluation

### Key Takeaways
- Several clinical and lifestyle variables were consistently associated
  with event risk
- Model calibration remained stable across multiple imputed datasets
- Bootstrapping confirmed robustness of selected predictors

### Tools
R, mice, glm, rms
