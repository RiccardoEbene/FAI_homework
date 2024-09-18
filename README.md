# Online News Popularity Prediction

This repository contains the implementation of various machine learning models to predict and classify the popularity of online news articles using the **Online News Popularity Dataset**. The dataset contains features extracted from news articles, and the goal is to either predict the number of shares (regression) or classify articles as popular or not (classification).

## Dataset

The dataset used in this project is the **Online News Popularity Dataset**, which consists of a variety of features such as article content, social media engagement, and others that can impact the popularity of the article. You can access the dataset [here](https://archive.ics.uci.edu/ml/datasets/online+news+popularity).

### Features:
- **61 attributes** including:
  - Content features (e.g., `n_tokens_content`, `n_unique_tokens`)
  - Social media engagement features (e.g., `num_videos`, `num_images`)
  - Day and channel information (e.g., `weekday_is_monday`, `is_weekend`, `data_channel_is_lifestyle`)
- **Target**:
  - For Regression: `shares` (the number of shares)
  - For Classification: A binary label derived from `shares`, where articles with more than a certain threshold of shares are labeled as "popular" and the others as "unpopular."

## Models Implemented

The project implements and evaluates various machine learning models for both regression and classification tasks. The following models were implemented:

### Regression Models
1. **Linear Regression**: A linear approach to model the relationship between features and the number of shares.
2. **K-Nearest Neighbors (KNN)**: A distance-based algorithm that predicts the number of shares based on the average of its nearest neighbors.
3. **Neural Network**: A deep learning model that predicts the number of shares using a multi-layer perceptron architecture.

### Classification Models
1. **Logistic Regression**: A simple and interpretable model to classify articles as popular or unpopular.
2. **K-Nearest Neighbors (KNN)**: A distance-based algorithm that classifies an article based on the majority class of its nearest neighbors.
3. **Decision Tree Classifier**: A tree-based model to classify the popularity based on article features.
4. **Neural Network**: A deep learning model to classify articles as popular or unpopular using a multi-layer perceptron architecture.




