# Learner Engagement Analysis & Prediction

## Project Overview

This project combines **data analytics, dashboard visualization, and machine learning** to analyze learner participation and predict learner engagement.

The project was developed in two major parts:

1. **Interactive Dashboard** – to explore learner participation, opportunity categories, engagement rates, statuses, and trends.
2. **Machine Learning Model** – to predict learner engagement using three classification models.

The machine learning models used in this project are:

* Logistic Regression
* Random Forest
* Gradient Boosting

---

## Business Problem

Organizations receive learner registrations and applications across different opportunities such as internships, courses, events, competitions, and other programs.

However, high participation does not always result in high engagement or successful completion.

This project aims to answer questions such as:

* Which opportunity categories attract the most learners?
* Which categories have better engagement rates?
* Where are learners dropping out or being rejected?
* How does learner participation change over time?
* Which areas may require better engagement strategies?
* Can machine learning help predict learner engagement?

---

# Part 1: Learner Analytics Dashboard

An interactive dashboard was developed to provide an overview of learner participation and engagement.

### Dashboard KPIs

The dashboard includes key metrics such as:

* Total Learners
* Total Opportunities
* Total Institutions
* Engagement Rate
* Engaged Learners

### Dashboard Analysis

The dashboard explores:

* Learner distribution by opportunity category
* Learner status and outcomes
* Engagement rate by opportunity category
* Engaged learners by category
* Learner signup trends over time
* Country-level opportunity outcomes
* Institution-level learner distribution
* Rejection and dropout patterns

### Key Dashboard Insights

* Internship opportunities attract a large share of learners but show a substantially lower engagement rate compared with other categories.
* Courses have fewer total learners than internships but contribute a higher number of engaged learners.
* Rejection and dropout outcomes represent important areas for investigation.
* High-volume countries and institutions contribute significantly to overall learner activity.
* Signup activity varies considerably over time, with noticeable peaks and declines.


# Part 2: Machine Learning

## Objective

The machine learning component focuses on predicting **learner engagement outcomes** using historical learner and opportunity data.

The objective is to identify patterns associated with learner engagement and evaluate different classification algorithms.

---

## Data Preprocessing

Before model training, the data was prepared through several preprocessing steps, including:

* Handling missing values
* Cleaning inconsistent values
* Converting date fields
* Reviewing suspicious records
* Preparing categorical and numerical features
* Encoding categorical variables
* Feature engineering
* Train/test splitting

---

## Machine Learning Models

### Logistic Regression

Logistic Regression was used as a baseline classification model. It provides an interpretable approach for estimating the likelihood of learner engagement.

### Random Forest

Random Forest uses multiple decision trees to capture more complex relationships within the dataset and improve classification performance.

### Gradient Boosting

Gradient Boosting builds models sequentially, with each model attempting to improve the errors made by previous models.

---

## Model Evaluation

The models were evaluated using multiple classification metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix
* ROC Curve

Using several evaluation metrics provides a more complete understanding of model performance rather than relying only on accuracy.

---

## Model Comparison

The three models were compared based on their evaluation results to identify the most suitable model for learner engagement prediction.

## Machine Learning Visualizations

### Confusion Matrix

The confusion matrix was used to examine correct and incorrect predictions for the engagement classes.



### ROC Curve

The ROC curve was used to evaluate how well the models distinguish between engagement outcomes.


# Recommendations

Based on the dashboard analysis and predictive modeling, the following recommendations can be considered:

1. **Target learners with lower predicted engagement**
   Use model predictions to identify learners who may benefit from additional communication or support.

2. **Investigate high rejection and dropout areas**
   Analyze eligibility requirements, application quality, opportunity requirements, and learner experience to understand negative outcomes.

3. **Improve internship engagement**
   Internship opportunities attract many learners but show comparatively lower engagement, making them an important area for improvement.

4. **Use data-driven learner follow-up**
   Combine dashboard insights with model predictions to prioritize learners and opportunities that require attention.

5. **Monitor engagement performance continuously**
   Regularly update the dashboard and re-evaluate model performance as new learner data becomes available.

6. **Use predictions as decision support**
   Machine learning predictions should support human decision-making rather than being treated as guaranteed outcomes.

---

# Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Data Preprocessing
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
Dashboard Development
     ↓
Train/Test Split
     ↓
Machine Learning
     ↓
Logistic Regression
Random Forest
Gradient Boosting
     ↓
Model Evaluation
     ↓
Insights & Recommendations
```

---

# Technologies Used

### Data Analysis

* Python
* Pandas
* NumPy

### Data Visualization

* Power BI / Dashboarding Tools
* Matplotlib

### Machine Learning

* Scikit-learn
* Logistic Regression
* Random Forest
* Gradient Boosting

### Development Environment

* VS code
* Python

---


# Conclusion

This project demonstrates an end-to-end approach to learner analytics by combining **data cleaning, exploratory analysis, dashboard visualization, machine learning, model evaluation, and business recommendations**.

The dashboard provides an overall view of learner participation and engagement patterns, while the machine learning component demonstrates how predictive models can be used to identify potential engagement outcomes.

Together, these approaches show how data can be transformed from raw records into **actionable insights and predictive decision support**.

