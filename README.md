# NYC-Taxi-STAT209

NYC Yellow Taxi Trip Total Payment Modeling
STAT 209 Final Project — Spring 2026
Authors: Mahnaz Pirgazi and Behzad FallahiFard


Project Overview

This project analyzes the factors associated with total payment amounts for NYC yellow taxi trips in January 2024. Using a 10% random sample of approximately 296,000 trips, we build and compare multiple regression models, including OLS, Ridge, LASSO, and PCR, to predict log-transformed total payment amount based on trip characteristics, geographic location, payment type, and temporal indicators.


Repository Contents

Final_project_Mahnaz_Behzad_STAT_209.qmd — Main analysis file containing all data cleaning, EDA, and modeling code
Final_project_Mahnaz_Behzad_STAT_209.html — Rendered output of the analysis


Data Source

The raw trip data used in this project is the NYC Yellow Taxi Trip Records for January 2024, publicly available from the NYC Taxi and Limousine Commission (TLC):
🔗 https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
To reproduce the results, download the January 2024 Yellow Taxi parquet file from the link above and place it in the same directory as the .qmd file.


How to Reproduce the Results

1. Clone or download this repository
2. Download the raw data from the TLC link above
3. Open the .qmd file in RStudio
4. Install any required packages listed at the top of the file
5. Run all chunks from top to bottom


Requirements

R version 4.0 or higher
Key packages: tidyverse, arrow, lubridate, corrplot, glmnet, pls, lmtest, car
