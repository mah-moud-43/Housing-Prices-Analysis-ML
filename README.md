# Housing Prices Analysis & Prediction (Real Estate)

This project explores housing market data to uncover patterns and build predictive models for estimating house prices based on property features. It combines data visualization, statistical analysis, and regression techniques to provide actionable insights in the real estate domain.

## 🎯 Objectives

- Analyze real estate data and identify key factors affecting housing prices.
- Perform feature engineering and data preprocessing.
- Build regression models to predict property prices accurately.
- Visualize trends and communicate insights for decision-making.

## 🏘️ Dataset Overview

The dataset includes features such as:

- `LotArea`, `OverallQual`, `YearBuilt`, `TotalBsmtSF`, `GrLivArea`
- `GarageCars`, `GarageArea`, `FullBath`, `TotRmsAbvGrd`
- `Neighborhood`, `HouseStyle`, `Exterior`, `Condition`, `SalePrice` (target)

## 📈 Key Insights

- **Overall Quality** and **GrLivArea (Above Ground Living Area)** have the strongest correlation with price.
- Newer houses and properties with larger garages or basements tend to be more expensive.
- **Neighborhood** plays a significant role in determining price — some neighborhoods are priced consistently higher.
- Houses with higher **Overall Condition** ratings still show variation in price due to size and style.

## 📊 EDA Highlights

- Correlation heatmaps and pairplots to identify strong predictors.
- Distribution plots and boxplots to study skewness and outliers.
- Log transformation used on `SalePrice` to reduce right skew.
- One-hot encoding applied to categorical variables like `Neighborhood`.

## 🤖 Machine Learning Models Used

- **Linear Regression**
- **Ridge & Lasso Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **XGBoost** (optional)

## 📊 Model Evaluation

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Cross-validation scores

**Best Model:** Gradient Boosting Regressor with RMSE ~22,000

## 🧠 Techniques Applied

- Handling missing values intelligently
- Feature selection & engineering
- Log transformation of skewed features
- Scaling numeric features
- Hyperparameter tuning with GridSearchCV

## 📁 Files Included

- `housing_analysis.ipynb` – EDA and feature engineering
- `housing_modeling.ipynb` – Model training and evaluation
- `housing.csv` – Dataset used
- `submission.csv` – Sample predictions for new data

## 🧠 What I Learned

- How to analyze real estate data and engineer meaningful features
- How to build, validate, and compare regression models
- How to interpret housing market trends from a data science perspective

## 🚀 Future Enhancements

- Integrate location coordinates and map visualizations
- Create a price estimation dashboard using Streamlit or Dash
- Use deep learning models for more complex predictions

---

## 🚀 Getting Started

To run the project:

```bash
git clone https://github.com/your-username/Housing-Prices-Analysis-ML.git
cd Housing-Prices-Analysis-ML
open housing_modeling.ipynb
