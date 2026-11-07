# Model Card — Agri Predictive Analytics Model

## Intended purpose
Demonstration of an early-warning district-level crop-yield forecasting workflow for a fictional Nagpur agritech startup. The forecast is framed as being issued at the end of agricultural week 20 to support procurement planning.

## Data
The project report states that the dataset is synthetic and seeded, with approximately 349,959 weekly rows across six districts and six crops. It was generated because no dataset was supplied with the internship brief. It is not official agricultural data and must not be presented as observed Vidarbha yields.

## Model
The report identifies a tuned Gradient Boosting Regressor, compared with a three-year rolling-mean baseline, Ridge Regression and Random Forest. The reported feature set contains 50 features, including lag, rolling and ratio features.

## Evaluation design
- Training period: 2006–2019
- Validation period: 2020–2022
- Test period: 2023–2025
- Reported test MAE: approximately 1.19 q/ha at district-crop level
- Reported test improvement over baseline: 31%

## Limitations and risks
- The dataset is synthetic; results do not establish real-world predictive performance.
- Test error was reported as approximately 40% higher than validation error. The stated stability criterion was not met.
- Performance weakened in unusually wet seasons.
- Price features are market signals, not causal agronomic drivers, and depend on timely mandi data.
- The report describes a permutation-sampling Shapley estimator because the SHAP package was unavailable in the offline environment.

## Appropriate use
Use this project as a reproducible learning demonstration. Validate and retrain with reliable real district-level data before any operational or procurement decisions.
