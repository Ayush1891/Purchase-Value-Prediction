# Predicting Customer Purchase Value

A machine learning project focused on building a regression model to predict the monetary value of customer purchases.

## 🌟 Project Overview

This repository contains a comprehensive data science project aimed at predicting the purchase value of customers. By analyzing historical transaction data and customer behavior, this project develops a predictive model that helps businesses forecast revenue, optimize marketing strategies, and personalize customer experiences. The model provides insights into which factors most influence a customer's spending, allowing for more informed business decisions.

The key stages of this project include:

- Data Preprocessing and Cleaning: Handling missing values, standardizing data, and preparing it for model training.

- Exploratory Data Analysis (EDA): Visualizing data to uncover patterns and relationships between customer attributes and purchase value.

- Feature Engineering: Creating new features from raw data (e.g., is_purchase, average purchase frequency) to improve model accuracy.

- Model Training and Evaluation: Building and training various regression models and evaluating their performance using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## 📊 Dataset

Source Link: [https://www.kaggle.com/competitions/engage-2-value-from-clicks-to-conversions/data](https://www.kaggle.com/competitions/engage-2-value-from-clicks-to-conversions/data)

The project relies on a dataset of customer transaction and behavioral data. While the specific dataset is hypothetical, it would typically contain features such as:

- User Behavior & Session Metrics

  - totalHits, pageViews, totals.bounces, new_visits, totals.visits: Indicators of user engagement and session activity.
  - sessionNumber, sessionStart: Information related to session sequence and timing.

- Device & Technical Attributes

  - deviceType, os, browser, screenSize, device.browserSize, device.language: Details about the user's device and browsing environment.
  - browserMajor, device.*: Encompasses a variety of device-level descriptors such as model, version, and screen specifications.
  - gclIdPresent: Signals the presence of a Google Click ID used in ad tracking.

- Traffic & Marketing Source

  - userChannel, trafficSource, trafficSource.medium, trafficSource.keyword, trafficSource.campaign: Insights into how users arrived at the platform.
  - trafficSource.adwordsClickInfo.*: Contains attributes from advertising sources, including ad network type and slot.
  - trafficSource.adContent, trafficSource.referralPath, trafficSource.isTrueDirect: Provide further attribution details.

- Geographical Context

  - geoNetwork.city, locationCountry, geoNetwork.continent, geoNetwork.subContinent, geoNetwork.metro, geoNetwork.region: Geographic identifiers to help understand regional behavior trends.
  - geoCluster, locationZone: Groupings based on geographic or behavioral patterns.

- Identifiers

  - userId, sessionId: Unique identifiers for each user and session, allowing for multi-session analysis.

- Target Variable

  - purchaseValue: The amount (in currency units) spent by the customer during the session. This is the target variable to be predicted.

---

## 🛠️ Technologies & Skills

- Python: The core programming language.

- Pandas & NumPy: For efficient data manipulation and numerical operations.

- Scikit-learn: The main library for building, training, and evaluating regression models.

- Matplotlib & Seaborn: For data visualization and exploratory data analysis.

- Regression Analysis: The fundamental machine learning technique applied in this project.

- Jupyter Notebooks: For an interactive development environment.

- Git & GitHub: For version control.
