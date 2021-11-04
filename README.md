#  Living in Nashville

## Overview
The fastest growing city in Tennessee is the Nashville-Davidson–Murfreesboro–Franklin metro area. Its population grew by 19.1% from 2010 to 2020 to 1,961,232 residents. During that same time, the population of Tennessee grew by 8.5%, and the U.S. population increased by 6.7%. 

With the COVID-19 pandemic a bit under control, the U.S. economy has made an incredible comeback. Consumer spending is strong, jobs are coming back, and the housing market is booming, and quite possibly the hottest it’s been in years.

Here locally in Middle Tennessee, there’s a new spotlight on our economic growth. Through several economic downturns, a massive flood, and tornadoes, Nashville has always shown resilience. Now is no different.

## Purpose
Our team lives in and around the Nashville area so as our final project, we chose to predict the sales price of housing in the Nashville Metro area based on key factors that may have influence on the price of the houses. 

Final determination was made to use Supervised Learning with the Regression model to minimize the error of prediction.  Through the ETL process, we will determine our features. The target will be the Sales Price.  For our machine learning model, we plan to begin with BalancedRandomForestClassifier to reduce bias.

The key steps are listed below:</br>

1. Framing the Problem - Complete</br>
2. Getting the Data - Complete</br>
3. Exploring the Data - Complete</br>
4. Data Preprocessing - In progress</br>
5. Model Development - In progress</br>
6. Model Tuning/Ensemble Learning </br>
7. Deploying Model </br>
8. Presentation of Solution - In progress</br>

## Resources:
Kaggle dataset:  https://www.kaggle.com/tmthyjames/nashville-housing-data/activity</br>
Enrollment - June 2021 from Metro Nashville Public Schools:  https://mnps.org/about/communications/opendata</br>
Parks:  https://data.nashville.gov/Parks/Park-Locations/74d7-b74t</br>
Restaurants/Social:  http://nashvilleguru.com/nashville-restaurants-and-bars</br>

## Software(s): 

SQLite, Python 3.7, Pandas, Numpy, Matplotlib, Scikit-Learn

## Presentation:</br>

Google Slides:  https://docs.google.com/presentation/d/1GFjG-l6xeNtwq9jgkAt1YndmvLPib42iHLwfS4r0gK8/edit?usp=sharing

### Week 1

* Created a branch for each section in the Rubric:  Presentation, Machine_Learning_Model, Database and Dashboard_Tableau

* Found several datasets as noted above. Each dataset needed manual editing in preparation to include zip codes as our common feature

* Determination was made to use pgAdmin for our server and AWS for our database

### Week 2

* Reviewed each dataset to determine the columns to drop and began Extract, transform, load (ETL) process on the data

* Created pg Admin server and AWS database and all team members connected

* Began creation of Machine Learning Model

* Began learning/working with Google slides

### Week 3

* ETL ipynb file is complete and uploaded to the Database_Nashville branch

* Google slide presentation in progress - shared link above

* Determined that using AWS to host our database was not necessary as we will use Tableau for our visualization

* Related to above, we also decided to use SQLite instead of pgAdmin for our database

* Machine Learning Model has been created as an outline and uploaded to the Machine_Learning_Model branch
