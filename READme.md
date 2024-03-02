# Bike and Pedestrian Traffic Incidents in Chicago

## Description

This project analyzes bike and pedestrian traffic incidents in Chicago, aiming to understand patterns and key factors contributing to crashes. By categorizing incidents into no injury, non-incapacitating injuries, and incapacitating injury/fatalities, we seek to improve road safety and prevent future accidents.

## Table of Contents

- [Background](#background)
- [Goals of Analysis](#goals-of-analysis)
- [Data Acquisition](#data-acquisition)
- [Model Preparation](#model-preparation)
- [Methodology](#methodology)
- [Model Interpretation](#model-interpretation)
- [Improvements](#improvements)

## Background

Chicago faces significant challenges in mitigating traffic accidents and improving road safety. Our project focuses on identifying patterns and key factors that contribute to traffic accidents, aiming to inform preventive measures.

## Goals of Analysis

The primary goals include understanding the distribution of bike and pedestrian traffic incidents, identifying contributing factors to different injury severities, and evaluating the effectiveness of road safety measures.

## Data Acquisition

Data was acquired via the Chicago Data Portal SOCRATA API, focusing on pedestrians and cyclists affected by traffic accidents in the last five years. The dataset includes over 22,000 records, with approximately 1,500 resulting in fatalities or incapacitating injuries.

## Model Preparation

The preparation involved cleaning the data, removing unnecessary columns, engineering the target variable, and encoding categorical features into integers. The target variable was categorized into three classes: no injury, non-incapacitating injury, and incapacitating injury/fatal.

## Methodology

Our analysis utilized various techniques including Principal Component Analysis (PCA), K-means clustering, t-Distributed Stochastic Neighbor Embedding (t-SNE), and Latent Class Analysis (LCA). We employed multiple algorithms for model building, such as Naïve Bayes, Logistic Regression, Support Vector Machines, Random Forest, Gradient Boosting, and Poisson Regression, with a focus on cross-validation using repeated k-Folds.

## Model Interpretation

The logistic regression model was particularly effective for predicting non-incapacitating injuries. By combining incapacitating and non-incapacitating injuries into a single variable, we found that the Random Forest model maintained strong accuracy, identifying key features contributing to severe outcomes.

## Improvements

Future improvements could include expanding data collection methods, incorporating more road safety sensors and studies, conducting thorough data audits and standardization, and enhancing accountability measures to further improve road safety in Chicago.

