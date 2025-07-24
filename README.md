Objective
Predict student performance (encoded Class) based on engagement metrics like raisedhands, VisITedResources, AnnouncementsView, and Discussion.

Approach
Data Preprocessing

Encoded categorical target (Class) numerically for regression.

Selected numerical features for modeling.

Model Training & Evaluation

Baseline (Linear Regression): Simple linear relationship between features and target.

Polynomial Regression (Degree=2): Captures non-linear patterns by adding quadratic terms.

Feature Experiments:

Experiment 1: Used only the two most impactful features (raisedhands, VisITedResources).

Experiment 2: Added manual squared terms (raisedhands², Discussion²) to improve non-linearity.

Performance Metrics

Evaluated models using Mean Absolute Error (MAE) and R² Score.

Visualized results to compare model effectiveness.

Key Findings
Polynomial regression often improves accuracy but risks overfitting.

Feature selection (Experiment 1) can simplify models without significant performance loss.

Manually adding squared terms (Experiment 2) can be an alternative to full polynomial expansion.

Dataset taken from keggle api token 
