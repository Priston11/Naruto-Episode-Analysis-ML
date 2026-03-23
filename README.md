# 🍥 Naruto Episode Success Analytics & Prediction

This project analyzes over 500 episodes of the *Naruto* series to identify the key drivers of viewer satisfaction (IMDb ratings). Using a combination of Exploratory Data Analysis (EDA) and Machine Learning, I built a model that predicts episode ratings with high precision.

## 🚀 Key Results
* **Model Performance**: Achieved an **88% R-squared score** and a **Mean Absolute Error (MAE) of 0.21**.
* **Primary Insight**: "Content Type" (Canon vs. Filler) is the #1 predictor of success, accounting for **47%** of the model's decision-making.
* **Engagement**: Community engagement (Votes) proved to be the second most influential factor (41%).

## 📊 Visual Insights
### 1. The "Filler" Penalty
Analysis shows a significant drop in ratings for filler content compared to Manga Canon arcs.
![Canon vs Filler](canon_vs_filler.png)

### 2. Rating Trends Over Time
Tracking the show's quality from its 2007 launch to its 2017 finale.
![Rating Trends](rating_trends.png)

## 🛠️ Tech Stack & Skills
* **Data Wrangling**: Cleaned messy Unicode data and handled time-series formatting using `Pandas`.
* **Visualization**: Developed professional-grade charts using `Seaborn` and `Matplotlib`.
* **Machine Learning**: Implemented a `RandomForestRegressor` with `GridSearchCV` for hyperparameter tuning.
* **Evaluation**: Validated model performance using R-squared and MAE metrics.

## 📂 Project Structure
- `naruto.ipynb`: Full Python source code and analysis.
- `naruto.csv`: Raw dataset.
- `final_naruto_episodes_analysis.csv`: Processed dataset with engineered features.
