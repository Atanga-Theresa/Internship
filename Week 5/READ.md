Project Overview

This project applies machine learning techniques to predict house prices based on various property features. Multiple regression models were trained, compared, and evaluated to identify the best-performing algorithm.

Dataset
Source: [Kaggle House Price Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
Target Variable: price
Features include:
Area
Bedrooms
Bathrooms
Stories
Parking
Furnishing status
Air conditioning
And other property attributes
Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

Models Implemented
Linear Regression (Baseline)
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Tuned Random Forest (GridSearchCV)

Evaluation Metrics
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score

Best Model

Gradient Boosting Regressor

Key Insights
Area is the most important predictor of house prices.
Ensemble models outperform single decision trees.
Gradient Boosting provided the best generalization performance.
Hyperparameter tuning does not always improve model performance.

Project Structure
Jupyter Notebook (model development)
Performance comparison report
