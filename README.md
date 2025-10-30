# Predicting Top-20 Performance in IFSC World Cup Climbing Events
I am Buket Çakır and this is my term project for DSA210.

---
<div align="center">

### Hypothesis: More events per season and higher average round score predict a Top-20 finish in a climbing World Cup event.

</div>
<p align="center">
  <img src="docs/assets/climbing_photo.jpg" alt="Climbing Competition Image" width="500">
</p>

# Project Overview

Climbing is a sport that combines physical strength, technique, problem-solving, and mental focus. In competition climbing particularly in IFSC World Cup events, athletes face routes designed to test their endurance, precision, and adaptability under time pressure.
This project aims to explore the relationship between athlete participation frequency, historical performance, and competitive success in professional sport climbing. The analysis will focus on identifying whether athletes who compete more frequently and maintain higher average scores, have a statistically higher likelihood of achieving a Top-20 finish in World Cup events.

# Data Collection
The dataset that will be used in this project will be obtained from Kaggle. It is titled as “IFSC Competition Climbing Results (1991–2024)” 

Source: https://www.kaggle.com/datasets/mxmlnv/ifsc-competition-climbing

This dataset contains publicly available results and athlete information scraped from the official IFSC website. It includes data on competition results, athlete profiles, and event details across multiple climbing disciplines from 1991 to 2024. 

The dataset consists of two files: one containing information about events such as competition name, year, location, discipline, and round, and another containing athlete-specific data including athlete name, nationality, rank, score, and time.


Since the dataset is already available publicly, the data collection step will involve:

-Downloading the dataset from Kaggle.

-Cleaning and organizing the data (handling missing values, filtering event types).

-Extracting the relevant variables such as number of events per athlete per season, average round scores, final ranking per competition.


# Planned Analysis

Exploratory Data Analysis (EDA): Distribution of rankings, event counts, and average scores, correlations between participation and placement.

Visualization: Scatter plots, trend lines, and discipline specific comparisons.


# Expected Outcome

The goal of this project is to understand how often athletes compete and how consistent their results are in relation to their overall success in climbing competitions. By the end, the project should produce a notebook that highlights relationships between key variables, identifies which factors seem to matter most for achieving top results, and includes clear visualizations showing performance trends across different years and climbing disciplines.

# Tools and Environment

Python (pandas, numpy, matplotlib, seaborn)

Google Collab

GitHub for version control and documentation


