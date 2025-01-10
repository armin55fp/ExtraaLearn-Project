# ExtraaLearn Project: EdTech Lead Conversion Analysis

## Overview

The **ExtraaLearn Project** analyzes the factors influencing lead conversion for an EdTech startup and builds machine learning models to predict potential paid customers. The project explores trends, evaluates customer profiles, and suggests actionable insights to enhance business strategies.

---

## Context

The EdTech industry is projected to grow significantly, with the online education market estimated at $286.62 billion by 2023. ExtraaLearn, a startup offering courses in cutting-edge technologies, faces challenges in identifying high-conversion leads. The goal is to prioritize resource allocation efficiently and improve conversion rates.

---

## Objectives

1. **Analyze**: Identify factors influencing lead conversion.
2. **Model**: Build classification models to predict lead conversion.
3. **Optimize**: Provide actionable insights for better resource allocation.

---

## Dataset

### Features:
- **Demographics**: Age, Current Occupation.
- **Behavior**: Website visits, Time spent on the website, Last activity.
- **Marketing Channels**: Print media, Digital media, Referrals.
- **Target Variable**: `Status` (0 = Not Converted, 1 = Converted).

---

## Methodology

### Data Preparation:
- Outlier detection and removal.
- Encoding categorical variables.
- Splitting data into training and test sets.

### Exploratory Data Analysis:
- Investigated feature importance through visualizations.
- Correlation analysis using heatmaps and pair plots.

### Models:
1. **Decision Tree Classifier**:
   - Tuned using grid search to reduce overfitting.
2. **Random Forest Classifier**:
   - Enhanced recall and generalization using hyperparameter tuning.

---

## Results and Insights

1. **Key Drivers**:
   - `Time Spent on Website`, `First Interaction`, and `Profile Completion` are the top features.
2. **Age and Occupation**:
   - Professionals aged 34–54 show the highest conversion rates.
3. **Referrals**:
   - Referral leads have the highest conversion rate (~70%).
4. **Optimized Models**:
   - Decision Tree and Random Forest models achieved recall scores of 0.80 and 0.82, respectively.

---

## Dependencies

The project requires the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`


