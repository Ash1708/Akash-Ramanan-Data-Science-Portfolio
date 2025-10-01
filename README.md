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


## 2. Sentiment-Analysis-on-IMDB-Reviews (Azure Data Factory + Azure Data Lake + Databricks (PySpark, scikit-learn) + Power BI)
https://github.com/Ash1708/The-Voice-of-the-Audience-Sentiment-Analysis-on-IMDB-Reviews/tree/main

### Project Overview
This project demonstrates how to build a full machine learning pipeline for sentiment analysis, leveraging Azure Databricks for large-scale training and Power BI for business insights. Using the IMDB reviews dataset, I implemented an NLP workflow that classifies movie reviews as positive or negative, and translated model results into actionable insights for decision-making.

### Tech Stack: Azure Data Factory, Azure Data Lake, Databricks (PySpark, scikit-learn), Power BI.

Highlights:
* Ingested IMDB dataset into Azure Data Lake and structured raw vs curated zones.
* Trained baseline Logistic Regression NLP model (TF-IDF + Logistic Regression).
* Exported predictions and built a Power BI dashboard with KPIs, confusion matrix, probability histograms, and misclassified reviews.
  
Results: Accuracy ~89%, F1-score ~89%, ROC-AUC ~96%.


Key Insight: Misclassification analysis revealed false positives lead to overestimated satisfaction, guiding customer feedback strategies.

