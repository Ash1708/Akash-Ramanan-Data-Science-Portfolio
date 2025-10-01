# Akash-Ramanan-Data-Science-Portfolio

### Welcome to my portfolio! I’m a Data scientist specialized in sports and business data with expertise in machine learning, statistics, and biomechanics, and hands-on experience building end-to-end data projects using Python, SQL, PowerBI and Cloud platforms.

### This repository serves as a landing page for my key projects, showcasing my skills across data engineering, machine learning, cloud deployment, and business insights.


# Projects
## 1. NYC Taxi Data Analysis (Azure data lake + Azure synapse + ADF + SQL + PowerBI Visualization)
[[https://github.com/Ash1708/NYC-Taxi-Analytics-Azure-PowerBI.](https://github.com/Ash1708/NYC-Taxi-Analytics-Azure-PowerBI./edit/main/README.md)](https://github.com/Ash1708/NYC-Taxi-Analytics-Azure-PowerBI./blob/main/README.md)

This project demonstrates a real-world data pipeline and business intelligence solution using
* Dataset: NYC Taxi Trip Records 2023 (public open data).
### Business Questions & Insights
#### Q1: How does taxi demand & revenue vary by month?
Insight: 
      
    * Seasonal variation visible; revenue trends follow trip volume.
#### Q2: Do more passengers mean longer trips or higher revenue?
Insight

    * Single-passenger trips dominate in volume.
    * Group trips (3–6+) are longer and generate higher revenue per trip.
    * Tip % varies by group size.
#### Q3: At what times of day and days of the week is demand highest?
Insight

    * Weekday peaks during morning/evening commute hours.
    * Weekend evenings to late-night peaks (Fri/Sat).


# 2. Sentiment-Analysis-on-IMDB-Reviews (Azure Data Factory + Azure Data Lake + Databricks (PySpark, scikit-learn) + Power BI)
https://github.com/Ash1708/The-Voice-of-the-Audience-Sentiment-Analysis-on-IMDB-Reviews/tree/main

### Project Overview
This project demonstrates how to build a full machine learning pipeline for sentiment analysis, leveraging Azure Databricks for large-scale training and Power BI for business insights. Using the IMDB reviews dataset, I implemented an NLP workflow that classifies movie reviews as positive or negative, and translated model results into actionable insights for decision-making.

### Tech Stack:
* Azure Data Factory, Azure Data Lake, Databricks (PySpark, scikit-learn), Power BI.

Highlights:
* Ingested IMDB dataset into Azure Data Lake and structured raw vs curated zones.
* Trained baseline Logistic Regression NLP model (TF-IDF + Logistic Regression).
* Exported predictions and built a Power BI dashboard with KPIs, confusion matrix, probability histograms, and misclassified reviews.
  
Results: Accuracy ~89%, F1-score ~89%, ROC-AUC ~96%.


Key Insight: Misclassification analysis revealed false positives lead to overestimated satisfaction, guiding customer feedback strategies.



# 3. Classification of Elite and sub elite Goalkeepers from professional football using multiple machine learning models (Internship Project)

https://github.com/Ash1708/Classification-of-Goalkeepers_ML/blob/main/README.md

Implemented a machine learning pipeline to classify elite vs. sub-elite goalkeepers using Opta football data. Compared Logistic Regression, Random Forest, and Gradient Boosting models, achieving ~67% accuracy and 0.72 ROC-AUC. Project demonstrates end-to-end ML skills: preprocessing, feature selection (RFE), cross-validation, model evaluation, and feature interpretability — with insights highlighting the importance of distribution and passing skills in modern elite goalkeepers.

* Built ML models to classify elite vs. sub-elite goalkeepers in top European leagues.
* Elite GK = UEFA Champions League appearance (proxy for top-tier status).
* Based on real-world Opta Sports performance data (14,671 match observations).

## Question 
* Which performance attributes best distinguish elite from sub-elite professional football goalkeepers, and can machine learning models reliably classify them based on match performance data?
  
## Libraries & Tools

* Data handling & preprocessing: Pandas, Numpy
* Machine learning & feature selection: Scikit-learn (Logistic Regression, Random Forest, Gradient Boosting, RFE, GridSearchCV, train/test split)
* Visualization: Matplotlib, Seaborn (confusion matrices, ROC curves, feature importance plots)
* Environment: Jupyter Notebook, Python 3.x

 ## Results

* Test accuracy: ~66–67% (similar across all models).
* ROC-AUC: ~0.72, F1 ≈ 0.65.

## Insights: Common features across models (n=15).

* Elite indicators: short distribution, passes received, successful forward passes, clean sheets.
* Sub-elite indicators: long distribution, unsuccessful opposition-half passes, more goals conceded.


# 4.👣 Project: Step Into the Data – Plantar foot Pressure Analysis for Biomechanics 

(Pressure measuring insoles, Python (pandas, numpy, scipy/statsmodels), matplotlib & seaborn for visualization)

https://github.com/Ash1708/Step-Into-the-Data-Plantar-foot-Pressure-Analysis-for-Biomechanics/blob/main/README.md

## Overview

* Investigated how plantar pressure distribution changes across different foot zones under static vs. dynamic conditions.
* Designed as an experimental biomechanics study, showcasing end-to-end statistical analysis.
* Goal: uncover patterns that could inform injury prevention, footwear design, and training practices.

### Analysis pipeline:

* Descriptive statistics + assumption checks (normality).
* Repeated-measures ANOVA to detect overall differences.
* Post-hoc paired t-tests to identify specific zone/condition effects.
* Tools: Python (pandas, numpy, scipy/statsmodels), matplotlib & seaborn for visualization.


## Key Insights

* Plantar pressure shifted dramatically from heel and midfoot → forefoot on unstable surfaces.
* Large effect sizes confirm these are not trivial differences, but substantial biomechanical shifts.
* Supports the view that unstable surfaces force greater forefoot loading, relevant for injury prevention, footwear design, and performance training.



