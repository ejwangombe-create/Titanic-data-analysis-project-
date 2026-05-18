# 🚢 Titanic Data Analysis

## Overview
Exploratory Data Analysis (EDA) of the Titanic dataset from Kaggle.

## What I analyzed
- Overall survival rate
- Survival by gender
- Survival by passenger class
- Survival by age

## Key Findings
- Women had a significantly higher survival rate than men
- 1st class passengers survived more than 2nd and 3rd class
- Young children were prioritized but small numbers made averages misleading

## Model Improvement Journey
| Model | Accuracy |
|-------|----------|
| Decision Tree | 77.7% |
| Random Forest | 82.1% |
| Random Forest + Feature Engineering | 82.7% |
| Tuned Random Forest | 80.4% |

## Key Insight
Family travelers had a 20.2% higher survival rate than solo travelers

## Best Model
Random Forest with Feature Engineering → 82.7% accuracy

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Dataset
[Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)

## Machine Learning
- Built a Decision Tree model → 77.7% accuracy
- Improved with Random Forest → 82.1% accuracy
- Top survival predictors: Fare, Sex, Age