# House Prices: Advanced Regression Techniques 🏠📊

This repository contains a complete solution for the Kaggle competition [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques), which challenges participants to predict the final price of homes in Ames, Iowa based on various features.

## 🧪 Approach

### 1. Data Preprocessing
- Combined train and test datasets for uniform preprocessing
- Handled missing values using domain knowledge
- Converted categorical variables using label encoding and one-hot encoding
- Applied log-transformation on the target variable (`SalePrice`)

### 2. Feature Engineering
- Created new features like total square footage, bathrooms per bedroom, etc.
- Applied skewness correction using Box-Cox transformation

### 3. Modeling Techniques
- **Lasso Regression**
- **Ridge Regression**
- **Gradient Boosting Regressor**
- **XGBoost**
- **LightGBM**
- **Stacked Regressor** 

### 4. Evaluation
- Used cross-validation (K-Fold) with RMSE as the evaluation metric
- Stacked model performed best with the lowest RMSE on validation

## 📈 Result

- Generated final predictions for the test dataset (`submission.csv`)
- Final file meets Kaggle’s submission requirements (1459 rows, header)
- Achieved competitive performance on the leaderboard


## ♎ Main Libraries

- `numpy`
- `pandas`
- `scikit-learn`
- `xgboost`
- `lightgbm`
- `seaborn`
- `matplotlib`

## 💻 Dependencies & Clone the Repository

First, clone the repository and navigate into the project folder:

```bash
git clone https://github.com/ananyagupta1812/house-prices-prediction.git
cd house-prices-prediction

pip install -r requirements.txt
