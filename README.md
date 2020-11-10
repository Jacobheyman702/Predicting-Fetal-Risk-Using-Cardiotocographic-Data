# Phase_3_Project


# Predicting Fetal Risk Using Cardiotocographic Data

**Authors**: Jacob Heyman, Ismael Araujo

## Overview
- Reducing fetal mortality a major goal of Medical Science
- Many fetal deaths are preventable and are the result of low available resources.
- Cardiotocograms are cheap and accesable solution for monitering fetal health. 
- CTGs provide data on fetal heart rate, fetal movements, uteraine contractions and more.
- Monitering the fetal heart rate allows for early detection of fetal distress.  
- These metrics can be used to predict the fetal health and prevent child mortality
- Our aim is to create a model that more accuratly detects fetel distress based on ctg data
- Our goal is to identify which features play a key factor in fetal distress
- The model will help drive decisions made on medical intervention



## Business Problem
Preventing Child mortality is a key indicator of medical progress.  A large precentage of deaths are the result of low access to resources that moniter fetal health.  One cost effective solution to moniter fetal health is the use of Cardiotocograms(CTGs). CTGs moniter fetal heart rate, fetal movement, uterine contractions, suddon heart rate changes and many other health metrics.  Using a kaggle database of collected CTG exams, we aim to identify which features have the most impact on fetal health being either normal or distressed.  


## Data
Our data came from Kaggle.com (https://www.kaggle.com/andrewmvd/fetal-health-classification).  The data comes from 2126 cardiotocogram measurments described in Ayres de Campos et al. (2000) SisPorto 2.0 A Program for Automated Analysis of Cardiotocograms. J Matern Fetal Med 5:311-318.  The CTG measurments where used to create a classification model to classify fetal health being either normal or distressed.  The DataFrame included the following columns:
** baseline_value - Baseline Fetal Heart Rate
** accelerations - Number of accelerations per second
** fetal_movement - Number of fetal movements per second
** uterine_contractions - Number of uterine contractions per second
** light_decelerations - Number of LDs per second
** severe_deceleration - Number of Sds per second
** prolongued_deceleration - Number of PDs per second
** abnormal_short_term_variatability - Percentage of time with abnormal short tearm variatability
** mean_value_of_short_term_variability - Mean value of short term variability
** percentage_of_time_with_abnormal_long_term_variability - Percentage of time with abnormal long term variability
** mean_value_of_long_term_variability - average value of long tearm variability
** histogram_width - Width of histogram using all the values from the record
** histogram_min - minimum value of histogram
** histogram_max - maximum value of hitogram
** histogram_number_of_peaks - number of peaks in the exam histogram
** histogram_number_of_zeroes - number of zeros in the exam histogram
** histogram_mode - histogram mode
** histogram_mean - histogram mean
** histogram_median - histogram median
** histogram_variance - histogram variance
** histogram_tendency - histogram tendancy
** fetal_health - 0: normal 1:distressed




## Methods
- data analysis and cleaning
- EDA
- Baseline models
- feature engineering
- modeling and hyperparameter tuning




## Results
- What features are the biggest factors in fetal health classification
- What our best model was
- Which features attributed to out best model



## Conclusions



## Next Steps

 

## For More Information





## Repository Structure

```
├── README.md                           <- 
├── overview_and_cleaning.ipynb         <- 
├── anaysis.ipynb                       <- 
├── Movie_Analysis_Presentation.pdf     <- 
├── helper_functions.py                 <- 
├── csv_to_clean_dataframes.py          <- 
├── exploration                         <- 
├── zippedData                          <- 
└──images                               <-  
```