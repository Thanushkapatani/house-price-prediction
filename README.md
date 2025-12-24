# Boston Housing Price Prediction

Project Overview
This project focuses on predicting median house prices (medv) using the Boston Housing dataset. An end-to-end machine learning workflow was implemented, including data exploration, preprocessing, model training, evaluation, and feature importance analysis.

Dataset
The Boston Housing dataset contains information about housing in different areas of Boston, with features such as crime rate, number of rooms, accessibility to highways, and pupil–teacher ratio.

Target Variable:
- medv: Median value of owner-occupied homes

Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

Exploratory Data Analysis (EDA)
- Distribution analysis of numerical features
- Boxplots for outlier detection
- Correlation heatmap to examine relationships between features
- Regression plots for key variables

Data Preprocessing
- Min–Max normalization
- Feature standardization using StandardScaler
- Feature selection
- Train–target split

Models Implemented
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

Model Evaluation
- Mean Squared Error (MSE)
- Five-fold cross-validation
- Feature importance comparison across models

Key Insights
- Tree-based models outperform Linear Regression
- XGBoost achieved the best overall performance
- Important features include lstat, rm, and ptratio

Conclusion
This project demonstrates a complete machine learning regression pipeline and highlights the importance of feature scaling, model comparison, and interpretability in predictive modeling.

