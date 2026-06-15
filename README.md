# melbourne-airbnb-price-prediction
BUSA8001- Applied predictive analytics
Melbourne Airbnb Price Prediction
Project Overview

This project predicts Airbnb listing prices in Melbourne using machine learning techniques and property-level features. The objective is to identify the factors influencing accommodation prices and develop an accurate predictive model to support pricing decisions.

Business Problem

Pricing is one of the most important decisions for Airbnb hosts.

Setting prices too high may reduce bookings, while pricing too low may result in lost revenue.

This project aims to:

Understand key drivers of Airbnb pricing
Analyse relationships between listing characteristics and price
Build machine learning models to predict listing prices
Compare model performance and identify the best solution
Dataset

Melbourne Airbnb Listings Dataset

Features include:

Property type
Room type
Location
Number of bedrooms
Bathrooms
Accommodates
Amenities
Availability
Host information

Target Variable:

Price
Project Workflow
1. Data Cleaning
Removed missing values
Handled inconsistent records
Created modelling dataset
2. Exploratory Data Analysis

Investigated:

Price distribution
Geographic trends
Property characteristics
Feature correlations

Key finding:

Individual variables showed relatively weak linear relationships with price, suggesting that more complex machine learning models may better capture pricing behaviour.

3. Feature Engineering

Created and transformed variables including:

Location indicators
Property characteristics
Accommodation capacity
Availability metrics
4. Model Development

Models tested:

Model	MAE
Random Forest	0.2347
XGBoost	0.2141
CatBoost	0.2131
