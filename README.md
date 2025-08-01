Healthy Life Expectancy Prediction with Gradient Boosted Decision Trees!
This project predicts healthy life expectancy at birth using the World Happiness Dataset and a Gradient Boosted Decision Regressor (GBDR). The aim is to build a reliable regression model and explore the bias-variance tradeoff to optimize performance and extract actionable insights for global health analysis.

About the data!
Source: World Happiness Dataset

Label: Healthy life expectancy at birth

Features: All remaining columns in the dataset excluding the label (e.g., GDP per capita, social support, freedom to make life choices, perceptions of corruption, etc.)

Problem Formulation!
Type: Supervised Learning
Model: Gradient Boosted Decision Regressor (GBDR)
Prediction Task: Regression
Goal: Predict a continuous target value (life expectancy)

Why This Problem Matters!
Predicting healthy life expectancy is valuable for public health policy, international aid, and social infrastructure development. A model like this could help identify at risk countries with low life expectancy, enabling early interventions to improve mental health, nutrition, and medical access in vulnerable regions.

Methodology!
- Trained three Gradient Boosted Decision Regressor models with varying max_depth (2, 10, and an optimized version)
- Performed a Grid Search for hyperparameter tuning on the best model

Evaluated models using:
- Mean Squared Error (MSE)
- Explained Variance Score (EVS)
- Bias^2
- Visualized the Bias-Variance Tradeoff across models

Key Takeaways and Analysis
- Shallow trees with a low depth show high bias but low variance
- Deep trees with a high depth reduce bias but can increase variance and risk overfitting
- Grid-searched model balanced generalization best, minimizing bias^2, variance, and mean squared error.
