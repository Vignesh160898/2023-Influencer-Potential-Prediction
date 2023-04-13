# Influencer-Potential-Prediction
Predicting influencer potential based on image and metadata features using machine learning algorithms
# Influencer Potential Prediction

This repository contains the Jupyter Notebook for the Kaggle competition titled "Can I be an influencer?" The goal of this competition is to predict the potential of an individual to become an influencer based on various image and metadata features.

## Table of Contents

1. [Dataset Overview](#dataset-overview)
2. [Feature Engineering](#feature-engineering)
3. [Model Selection](#model-selection)
4. [Results](#results)



## Dataset Overview

The dataset consists of a variety of image features, including:

- Image dimensions (width and height)
- Camera metadata (camera make, model, ISO, aperture value, focal length, etc.)
- Keywords associated with the image
- Color scores
- Image classifications and confidence values

## Feature Engineering

The following feature engineering steps have been performed in the notebook:

1. Extracting and aggregating top 5 classification keywords for each image
2. Generating word embeddings for keywords
3. Filtering color keywords based on their occurrence frequency
4. Cleaning and standardizing camera make names
5. Merging dataframes and handling missing values
6. One-hot encoding categorical features
7. Scaling numerical features

## Model Selection

We have tested several machine learning models, including:

1. Linear Regression
2. Support Vector Regression (SVR)
3. XGBoost
4. Random Forest
5. CatBoost
6. Lasso Regression
7. Ridge Regression
8. ElasticNet
9. Neural Networks (using TensorFlow)

## Results

The notebook contains the evaluation metrics (R^2 and adjusted R^2 scores) for each model on the test dataset. You can compare the results to select the best model for your specific use case.

