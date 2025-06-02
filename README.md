# 🏏 Cricket Data Analysis & Score Prediction

A data science project using machine learning regression to analyze cricket match data and predict team scores. It explores player performance, match conditions, and historical stats to uncover patterns and improve prediction accuracy—ideal for fans, analysts, and strategists.

---

## 📌 Project Overview

This project combines **data science** and **machine learning** to analyze historical cricket match data and build a predictive model capable of forecasting team scores. The main objective is to apply **regression techniques** to uncover how various features — such as player performance, innings details, overs remaining, pitch conditions, and more — influence the final score of a team in a match.

By focusing on a practical and popular sport like cricket, the project highlights the real-world applications of data science in sports analytics. It also serves as a hands-on opportunity for exploring data preprocessing, feature engineering, model selection, and evaluation.

Whether you are a data science enthusiast, cricket fan, or sports strategist, this project provides valuable insights into the performance dynamics of cricket matches.

---

## 🎯 Objectives

- Analyze and visualize cricket match data to identify key performance indicators
- Build regression models to predict a team’s total score in limited-over matches
- Perform data cleaning, feature extraction, and transformation for model readiness
- Compare performance across different regression algorithms
- Generate insights useful for analysts, teams, and fans

---

## 🧠 Problem Statement

**Can we accurately predict the final score of a cricket team using machine learning models, based on the current match situation (e.g., overs completed, wickets fallen, current batsmen, run rate, and more)?**

Understanding this problem helps teams strategize better, commentators offer data-driven analysis, and fans engage deeper with the sport.

---

## 📂 Dataset

The dataset contains match-by-match information such as:

- Batting team & bowling team
- Overs completed
- Runs scored
- Wickets fallen
- Players at the crease
- Venue
- Run rate
- Historical statistics (optional depending on dataset)

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed during EDA:

- Distribution of scores across different stadiums
- Impact of number of wickets fallen on total score
- Score progression over overs
- Player-specific performance trends
- Correlation heatmap to examine feature relationships

These visualizations provided valuable direction for feature selection and model tuning.

---

## 🏗️ Methodology

### 1. **Data Cleaning**
- Removed null values and irrelevant columns
- Filtered out matches with incomplete data
- Encoded categorical variables (teams, players, venue)

### 2. **Feature Engineering**
- Created new features like `current run rate`, `runs remaining`, `balls remaining`, `wickets in hand`
- One-hot encoded categorical features

### 3. **Model Selection**
Applied and compared the following regression models:

- **Linear Regression**
- **Ridge & Lasso Regression**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **XGBoost Regressor**

### 4. **Model Evaluation**
Used the following metrics to evaluate performance:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**, **NumPy** – Data handling
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – Machine learning models
- **Jupyter Notebook** / **VS Code** – Development environments

---

## 📊 Results

After training and evaluating multiple regression models, the **Random Forest Regressor** and **XGBoost Regressor** consistently delivered the most accurate predictions, with lower MAE and RMSE compared to other models. Feature importance analysis revealed that overs left, wickets in hand, and current run rate were highly predictive of the final score.

Visualizations were used to compare predicted vs actual scores and analyze prediction errors.

---

## 🌐 Real-World Applications

- **Cricket Teams** – Optimize game strategy based on predictive scoring trends
- **Broadcasters & Analysts** – Deliver real-time data-driven insights during live matches
- **Fantasy Leagues** – Improve player selection strategies
- **Fans** – Enhance understanding and engagement with the game through data

---

## 🚀 Getting Started

### 🔧 Prerequisites

Make sure you have Python 3.x installed. Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
# Cricket Score Prediction



