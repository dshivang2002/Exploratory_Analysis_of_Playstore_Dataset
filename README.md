# 🚀  Play Store App Analysis

This repository contains a detailed cleaning process on uncleaned app data and then performed exploratory data analysis (EDA) and feature engineering (FE) process on this cleaned dataset of Android apps from the Google Play Store . On performing operations got some observation and insights of the playstore dataset .

--- 

## 📊 Dataset

The dataset `App_Detailed_cleaned.csv` includes various attributes about Android apps such as category, ratings, number of installs, price, content rating, and more.

## 📚 Feature Information
**1. App :-** Name of the App  

**2. Category :-** Category under which the App falls.  

**3. Rating :-** Application's rating on playstore.  

**4. Reviews :-** Number of reviews of the App.  

**5. Size :-** Size of the App.  

**6. Install :-** Number of Installs of the App.  

**7. Type :-** If the App is free/paid.  

**8. Price :-** Price of the app (0 if it is Free).  

**9. Content Rating :-** Appropiate Target Audience of the App.  

**10. Genres:-** Genre under which the App falls.  

**11. Last Updated :-** Date when the App was last updated.  

**12. Current Ver :-** Current Version of the Application.  

**13. Android Ver :-** Minimum Android Version required to run the App. 

--- 
## 🛠️ Steps include in Jupyter Notebook 

This Jupyter notebook includes:

### 1️⃣ Data Loading and Overview
- Understanding dataset dimensions
- Displaying first few rows
- Checking data types

### 2️⃣ Data Cleaning
- Handling missing values
- Converting string-based numbers (like "1,000+") into numeric types
- Replace and drop unnecessary values and literals 
- Formatting price and install values
- Extracting the some information(like Day , Month and Year ) from we have already 

### 3️⃣ Exploratory Data Analysis (EDA)
- Visualizing distribution of ratings
- Perform some Univariate Analysis , Bivariate and Corealational Analysis
- Analyzing number of installs vs. ratings
- Top categories by number of apps.
- Most installed Apps in Each popular Categories.
- Correlation heatmaps

### 4️⃣ Feature Engineering (FE)
- Creating new features like app age
- Converting categorical columns to numerical
- Normalizing numerical values

### 5️⃣ Visualizations
- Histograms, box plots, scatter plots
- Category-wise comparisons
- Interactive plots with Plotly
---

## 📝 Insights  
- Most popular game is Subway Surfers.
- Most popular communication app is Hangouts.
- Most popular productivity app is Google Drive.
- Most popular social app is Instagram.
- There are 271 five rated apps on Google Play store
- Top most is 'CT Brain Interpretation' from 'Family' Category

## 📦 Requirements
- pandas
- numpy
- matplotlib
- seaborn
= plotly
- scikit-learn
- jupyter


