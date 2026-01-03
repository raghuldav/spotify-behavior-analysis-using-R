# 🎧 Spotify Music Listening Behavior Analysis

## Overview
This project analyzes **global Spotify chart data from 2014 to 2022** to uncover patterns and trends in music listening behavior over time. Using **R**, along with statistical and machine learning techniques, the study explores temporal trends, listener behavior clusters, and structural changes influenced by major global events such as the **COVID-19 pandemic**.

The analysis provides insights into how music popularity evolves across countries, how long songs survive on charts, and how streaming behavior shifted during and after the pandemic.

---

## Project Structure
- **Spotify_ProjectReport_code_final.Rmd**  
  Complete R Markdown file containing data preprocessing, analysis, modeling, and visualizations.

- **Spotify Music Listening Behaviour.pdf**  
  Final project report summarizing key findings and interpretations.

- **data/**  
  Dataset sourced from Kaggle:  
  https://www.kaggle.com/datasets/jfreyberg/spotify-chart-data

---

## Objectives
This project aims to mine large-scale Spotify chart data to uncover:
- Temporal trends in streaming activity  
- Geographic differences in music popularity  
- Listener behavior patterns using clustering techniques  
- Structural changes caused by the COVID-19 pandemic  
- Survival patterns of songs on Spotify charts  

---

## Techniques Used
- **Exploratory Data Analysis (EDA)**  
- **Principal Component Analysis (PCA)**  
- **Hierarchical Clustering**  
- **Time Series Forecasting (ARIMA)**  
- **Change Point Detection (CUSUM, e.divisive)**  
- **Survival Analysis (Kaplan–Meier Estimation)**  

---

## Key Results
- The **United States, Switzerland, and Poland** recorded the highest number of chart entries.
- Streaming activity exhibited **seasonal patterns** and significant shifts during the COVID-19 period.
- PCA revealed a strong **inverse relationship between streaming volume and chart position**.
- Clustering separated songs into **low, medium, and high streaming groups**.
- ARIMA models forecasted a **post-2023 recovery** in streaming volumes.
- Major change points were detected in **early 2020** and **late 2021**, aligning with pandemic phases.
- Survival analysis showed that **Top 10 songs remained on the charts significantly longer** than others.

---

## Libraries Used
- tidyverse, ggplot2  
- survival, survminer  
- changepoint, ecp  
- forecast, tseries  

---

## How to Run
1. Install the required R packages:
   ```r
   install.packages(c(
     "tidyverse", "ggplot2", "survival", "survminer",
     "changepoint", "ecp", "forecast", "tseries"
   ))
2. Open Spotify_ProjectReport_code_final.Rmd in RStudio.

3. Run the R Markdown file to generate all visualizations, analyses, and results.

## Conclusion

This project demonstrates how statistical modeling and machine learning techniques can be applied to large-scale music streaming data to uncover meaningful behavioral insights. The findings highlight the impact of global events on listening patterns and provide a data-driven understanding of music popularity dynamics over time.


---

If you want next:
- **Short version for GitHub profile Overview**
- **Resume bullet points**
- **Academic-style abstract**
- **Add charts preview section**

Just tell me 👍
