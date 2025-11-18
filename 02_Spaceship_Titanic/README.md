#  Spaceship Titanic – Classification  
Kaggle Link: https://www.kaggle.com/competitions/spaceship-titanic

##  Goal  
Predict which passengers were transported to an alternate dimension after a spaceship collision.

##  Data Processing  
- Filled missing cabin, age, home planet info  
- Extracted new features from Cabin (Deck, Side)  
- Converted categorical variables with Label Encoding  
- Standardized numeric columns  

##  Models Trained  
| Model | Accuracy | Notes |
|--------|----------|--------|
| Logistic Regression | baseline | simple model |
| RandomForestClassifier | improved | handled feature interactions well |
| XGBoost | best | final Kaggle submission |

Final model: **XGBoost** tuned with grid search.

##  Evaluation  
Metric: **Accuracy**  
Public Leaderboard Score: *(add your exact score)*

##  Files  
- `Spaceship Titanic.ipynb` – full pipeline  
- `submission.csv` – final predictions  

##  Future Work  
- Add LightGBM  
- Tune hyperparameters with Optuna  
- Ensemble models for higher accuracy  
