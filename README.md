# 🌍 Predicting Country Happiness with Machine Learning

This project uses the **World Happiness Report (WHR)** dataset to predict a country's happiness score based on social, economic, and government indicators. We explore multiple regression models and compare their performance to determine what best predicts happiness levels around the world.

## 📊 Project Overview

- **Goal**: Predict the **Happiness Score** (formerly called *Life Ladder*) for each country-year using selected features.
- **Models Used**:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor

We evaluate performance using **R² score** and **Root Mean Squared Error (RMSE)**.

## 🧠 Machine Learning Pipeline

1. **Data Cleaning**
   - Dropped rows with missing values
   - Renamed features for clarity
   - Identified potential outliers

2. **Feature Engineering**
   - Selected key predictors (GDP, Social Support, Life Expectancy, etc.)
   - Scaled feature values

3. **Model Training & Evaluation**
   - Trained and tested Linear Regression, Decision Tree, and Random Forest models
   - Visualized predictions vs actual values
   - Compared model performance using bar plots

## 📈 Results Summary

| Model              | R² Score | RMSE  |
|-------------------|----------|--------|
| Linear Regression | 0.970    | 0.17   |
| Random Forest     | 0.957    | 0.209  |
| Decision Tree     | 0.850    | 0.39   |

**Linear Regression** gave the best balance of simplicity and accuracy.

## 🛠 Tech Stack

- **Python 3**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computations
- **Scikit-learn** – ML models and preprocessing
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive development

## 📁 Dataset

- [World Happiness Report](https://worldhappiness.report/)  
- Columns include: GDP, Social Support, Healthy Life Expectancy, Freedom, Generosity, Government Trust, Emotions, GINI Indexes, etc.

## 💡 Key Learnings

- Linear Regression is strong for understanding feature importance.
- Random Forest handles non-linear relationships better but is less interpretable.
- Social and political factors (like trust in government and freedom) significantly impact happiness scores.

## ✅ Future Work

- Handle missing data with imputation instead of row drops
- Use Ridge or Lasso Regression for regularization
- Try advanced models (e.g., XGBoost)
- Deploy as a simple app with Streamlit

---

