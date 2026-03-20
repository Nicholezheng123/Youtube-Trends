<p align="left">
  <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg" width="180"/>
</p> # YouTube Trends Analysis & Prediction

**Cornell INFO 2950 Final Project**  
**Authors:** Nichole Zheng, ys565, nz268  

---

## Project Overview

This project analyzes the factors that influence YouTube videos to trend across multiple countries using daily trending datasets.

The goal is to combine data cleaning, exploratory analysis, and predictive modeling to better understand what drives video popularity and whether trending behavior can be predicted.

---

## Objectives

- Identify key factors that influence trending videos  
- Analyze engagement metrics such as views, likes, and comments  
- Compare trends across countries  
- Build models to predict whether a video will trend  

---

## Methods

### Data Processing
- Cleaned and merged datasets from multiple countries  
- Handled missing values and inconsistent formatting  
- Created new features, including:
  - Like-to-view ratio  
  - Comment-to-view ratio  
  - Time between publish date and trending date  

---

### Exploratory Data Analysis
- Analyzed distributions of views, likes, and comments  
- Examined category-level trends (e.g., Music, Entertainment)  
- Compared patterns across countries  
- Studied correlations between engagement metrics  

---

### Predictive Modeling
- Built classification models to predict trending status  
- Techniques explored:
  - Logistic Regression  
- Model evaluation metrics:
  - Accuracy  
  - Precision and Recall  

---

## Key Findings

- Engagement metrics are stronger indicators than raw view counts  
- Categories such as Music and Entertainment dominate trending content  
- Videos that trend shortly after publishing perform better  
- There are noticeable differences in trends across countries  

---

## Tools and Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## Dataset

The dataset consists of daily YouTube trending data across multiple countries.

Link: https://drive.google.com/drive/folders/1v1HBn_7LQqFJk9JjoD-FXTBwBys4sFP-?usp=sharing

---

## What I Learned

- Cleaning and structuring real-world datasets  
- Performing exploratory data analysis to uncover patterns  
- Building and evaluating predictive models  
- Communicating insights through visualizations  

---

## Future Improvements

- Explore more advanced models such as Random Forest and XGBoost  
- Incorporate NLP techniques on video titles and descriptions  
- Apply time-series analysis for trend prediction  
- Develop an interactive dashboard for visualization  
