# Titanic Survival Prediction باستخدام Machine Learning

## Project Overview
This project demonstrates the application of machine learning techniques to predict passenger survival on the Titanic dataset. It is a classic binary classification problem where the goal is to determine whether a passenger survived or not based on features like age, gender, class, and fare.

The project includes:
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Model training and evaluation
- Feature importance analysis

---

## Dataset
The dataset used is the **Titanic dataset** from Kaggle:
- Contains passenger information such as:
  - Age
  - Sex
  - Passenger class (Pclass)
  - Fare
  - SibSp (siblings/spouses)
  - Parch (parents/children)
  - Embarked
- Target variable:
  - `Survived` (0 = No, 1 = Yes)

---

## Exploratory Data Analysis
EDA was performed to understand:
- Survival distribution (imbalanced dataset)
- Impact of gender on survival
- Effect of passenger class
- Age and fare distributions

Key findings:
- Females had higher survival rates
- First-class passengers were more likely to survive
- Fare correlates with survival (proxy for wealth)

---

## Machine Learning Models Used

### 1. Logistic Regression
- Simple and interpretable linear model
- Accuracy ≈ 81%
- Good baseline model

### 2. Decision Tree
- Non-linear model
- Accuracy ≈ 80%
- Easy to interpret but prone to overfitting

### 3. Random Forest 
- Ensemble model using multiple decision trees
- Accuracy ≈ 81%
- Best overall performance with balanced predictions

---

## Model Comparison
| Model               | Accuracy | Notes                          |
|--------------------|----------|--------------------------------|
| Logistic Regression| ~0.81    | Interpretable baseline         |
| Decision Tree      | ~0.80    | Slight overfitting             |
| Random Forest      | ~0.81    | Best overall performance       |

---

## Feature Importance
Top features influencing survival:
- Fare
- Sex
- Age

---

## ⚙️ Project Structure
