# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Group Project by Dolphin Sharma and Charles Crocicchia

## Problem Statement
This project aims to analyze the influence of corn and soybeans, America's most farmed corps, on key economic indicators in rural U.S. areas for approximately 15 years. By examining crop-related production and sales metrics this analysis seeks to identify correlations between crop production trends and rural economic development. We will investigate whether corn and soybean production data can be used to forecast changes in rural employment, income, and poverty levels. The goal is to assess the long-term economic impacts of crop productivity and sales on rural communities and to explore the predictive potential of corn data for future economic outcomes like employment, personal_income, and poverty levels.

---

**Goals**

- *Analyze the influence of corn and soybean production on rural 
economic indicators (employment, income, poverty).*
- *Identify correlations between corn and soybean production metrics 
(e.g., acres planted, yield, production volume, cash receipts) and rural
economic development indicators.*
- *Forecast economic outcomes based on corn and soybean 
production trends (can corn or soybean production be used to predict 
employment, income, and poverty levels?).*
- *Assess the long-term impacts of corn and soybean productivity on 
rural economic outcomes.*

---

### Table of Contents

 1. [EDA (Part 1)](part_1_eda.ipynb)
 2. [EDA (Part 2)](part_2_eda.ipynb)
 3. [Cleaning](part_3_data_cleaning.ipynb)
 4. [Preprocessing](part_4_data_preprocessing.ipynb)
 5. [Modeling](part_5_data_modeling.ipynb)

---

### Data Overview
[Data Dictionary](data_dictionaries.md)

Agricultural data was collected from [USDA National Agricultural Statistics Service](https://quickstats.nass.usda.gov/), economic data was collected from [Bureau of Economic Analysis](https://www.bea.gov/data), and downloaded in .csv format. These datasets held the metrics of corn and soybean productions along with the economic factors corresponding with state and time. Steps were taken to standardize naming of columns and reshaping/merging datasets in order to conduct proper EDA and modeling on the metrics of corn and soybean production. Since the data was organized by state and time, we were able to identify which states did not record corn/soybean data and properly account for these missing values in our EDA/modeling. No missing values needed to be addressed in the economic data sets. Once we were able to clean the data sufficiently, we merged these datasets in our preprocessing stage, which allowed us to work on modeling in a much more succinct manner.

---


### Software Requirements

The following Python libraries were used to conduct our research:

 - Pandas
 - Numpy
 - Scikit-learn
 
