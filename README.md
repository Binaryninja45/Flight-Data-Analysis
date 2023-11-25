# Flight-Data-Analysis
# Overview
* Explored and analyzed a dataset containing information about flights.
* Investigated the dataset's structure, identified missing values, and performed essential data type conversions.
* Utilized descriptive statistics to gain insights into the distribution of numerical and categorical features.
# Exploratory Data Analysis (EDA)
__Numerical Features__
* Conducted thorough analysis of numerical features such as 'day', 'month', 'dep_time', 'dep_delay', 'arr_delay', and more.
* Plotted histograms to visualize the distribution of flight-related attributes, revealing patterns and outliers.
__Categorical Features__
* Explored categorical features like 'year', 'carrier', 'origin', 'name', and 'dest'.
* Utilized bar plots to showcase the frequency distribution of airlines, origins, destinations, and more.
__Data Preprocessing__
* Dropped unnecessary columns ('id', 'year', 'flight', 'tailnum', 'time_hour', 'minute', 'hour', 'carrier').
* Addressed missing values through targeted removal and K-Nearest Neighbors (KNN) imputation.
* Applied one-hot encoding to categorical features ('origin', 'name') and frequency encoding to 'dest'.
__Outlier Treatment__
* Recognized outliers and their impact on machine learning models.
* Implemented outlier treatment techniques to enhance model robustness.
__Features Encoding__
* Identified and categorized categorical columns for encoding.
* Applied one-hot encoding to certain features ('origin', 'name') and frequency encoding to 'dest' for improved model compatibility.
__Conclusion__
* This comprehensive analysis and preprocessing prepare the dataset for further machine learning tasks.
* The cleaned and enriched dataset sets the stage for predictive modeling and advanced analytics.
__Dependencies__
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* imbalanced-learn
* pycountry-convert
* xgboost
