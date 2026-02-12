# SyriaTel Customer Churn Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0+-orange.svg)

##  Overview

A machine learning classification project to predict customer churn for SyriaTel telecommunications company. The model identifies customers likely to discontinue service, enabling proactive retention strategies and reducing revenue loss.

##  Business Problem

**Challenge**: SyriaTel experiences 14.5% customer churn, resulting in significant revenue loss.

**Objective**: Build a binary classifier to predict which customers will churn based on account information and usage patterns.

**Impact**: Enable targeted retention campaigns and reduce customer attrition.

##  Dataset

- **Source**: SyriaTel Customer Churn Dataset
- **Size**: 3,333 customer records
- **Features**: 21 columns (account info, usage metrics, service plans)

## Methodology

1. **Data Exploration**: Analyzed patterns, distributions, and correlations
2. **Feature Engineering**: Created aggregate features (total minutes, calls, charges)
3. **Preprocessing**: Encoded categorical variables, scaled features, train-test split (80/20)
4. **Modeling**: Trained Logistic Regression, Decision Tree, Random Forest, Gradient Boosting
5. **Evaluation**: Compared models using accuracy, precision, recall, F1-score, ROC-AUC 

##  Results

### Best Model: Random Forest (Tuned)

| Metric | Score |
|--------|-------|
| Accuracy | 94.3% |
| Precision | 87.5% |
| Recall | 78.2% |
| F1-Score | 82.6% |
| ROC-AUC | 91.7% |

### Top Churn Predictors

1. **Customer Service Calls** - 4+ calls indicate 50%+ churn risk
2. **International Plan** - 42% churn rate vs 11% without plan
3. **Total Day Charge** - High charges correlate with churn
4. **Total Day Minutes** - Usage extremes predict churn
5. **Voice Mail Plan** - Protective factor against churn

### Key Insights

- International plan subscribers churn at **4x** the normal rate
- Customers with **4+ service calls** have **50%+ churn probability**
- **Geographic variation**: Certain states show significantly higher churn
- **High charges** are strong churn predictors

##  Business Recommendations

### 1. Improve Customer Service Quality
- Root cause analysis for repeated service calls
- First-call resolution training
- **Expected Impact**: 15-20% churn reduction

### 2. Review International Plan
- Competitive pricing analysis
- Survey customer pain points
- **Expected Impact**: Reduce plan churn from 42% to <25%

### 3. Deploy Proactive Retention Program
- Real-time risk scoring using this model
- Automated alerts for high-risk customers
- Targeted retention offers
- **Expected Impact**: Save $4.17M annually

### 4. Geographic Targeting
- Focus resources on high-churn states
- Investigate regional competitive threats
- **Expected Impact**: 10-15% state-specific reduction

##  Author

**Your Name**
- GitHub: [@monicahwairimu](https://github.com/monicahwairimu124)
- Email: monicahwairimu124@gmail.com

