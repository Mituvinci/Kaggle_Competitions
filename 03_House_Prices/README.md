#  House Prices – Advanced Regression Techniques  
Kaggle Link: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

##  Goal  
Predict the final sale price of homes based on 79 explanatory variables covering location, quality, and condition features.

##  Data Preprocessing  
- Handling missing values (LotFrontage, GarageType, Basement variables, etc.)  
- Converting categorical variables using one-hot encoding  
- Log-transforming skewed numeric features  
- Standardizing continuous variables  

##  Models Trained  
| Model | Score | Notes |
|-------|--------|-------|
| Linear Regression | baseline | simple baseline |
| RandomForestRegressor | improved | handled non-linearities |
| XGBoost | best score | tuned hyperparameters |

Final model: **XGBoost** with optimized learning rate, max depth, and subsample.

##  Evaluation  
Metric: **Root Mean Squared Log Error (RMSLE)**  
Achieved score: *(add your public score once checked)*

##  Files  
- `house_prices.ipynb` – full data cleaning + modeling pipeline  
- `submission.csv` – Kaggle submission file  

##  Future Improvements  
- Add CatBoost for categorical-heavy dataset  
- Advanced stacking/ensembling  
- Feature selection based on mutual information
