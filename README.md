# Medical Appointments No-Shows

## Overview
The goal of this project is to investigate a dataset of appoinment records for Brasil public hospitals. The data includes some attributes of patients and state if the patients showed up to appointments. The analysis should be focused on finding trends influencing patients to show or not show up to appointments. Using **descriptive statistics** the following question should be answered: What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment? Predictive analytics is out of scope of this project.

The original problem description and data set can be found here: https://www.kaggle.com/joniarroba/noshowappointments/home


## Details
I have looked into the dataset and managed a few problems like removing wrong data, adding new features based on existing data. I have also investigated most of the independent variables in the dataset and made a few observations comparing them to each other as well as to the independent variables (Show). As this was only an exploratory analysis, many potential correlations may remain uncovered.


## Findings
The most important findings are:
- The appointment scheduling started on November, 10th 2015 as at 07:13 AM.
- The appointment scheduling ended on June, 8th 2016 as at 08:07 PM.
- The visit appointment started on April, 29th 2016.
- The visit appointment ended on June, 8th 2016.
- The distribution of appointments among days of week (Monday-Friday) is almost equal with a little less visits on Thursday and Friday.      There are only 39 visits on Saturday with none on Sunday.
- The distribution of appointments among month of the year (April-June). May and June record 80841 and 26451 visits respectively. There are only 3235 visits for the month of April.
- There are many infants (patients of age 0) in the dataset. Patients age values are evenly distribution and the number of patients goes drastically down for patients older than years.
- The patients are 37 years on average. 25% of the patients are below 18 and majority of the patients are below 55. 
- Most of the patients are not alcoholics.
- Most of the patients are not diabetes.
- There are four categories for the handcap with most of the patients not being handicapted.
- Most of the patients do not have hypertension diagnosed.
- On avearge only 20% of the appointments were missed.
- Out of 71831 appointments made by females, 14588 were missed with the ratio of 20%.
- Out of 38685 appointments made by males, 7723 were missed with the ratio of 20%
- There are multiple appointments. The number ofappointment of top 20 patients range from 88 to 38.

## Statistical Analysis Scope
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Examination of central tendency and spread
- Data visualizations

## Tools
- Python, libraries: numpy, pandas, matplotlib, seaborn, datetime.
- Jupyter Lab