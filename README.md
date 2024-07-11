# YouTube Channel Analysis and Growth Prediction Project
This repository contains the code and data used for a comprehensive analysis of the top 1000 YouTube channels and the development of a machine learning model to predict a channel's growth based on certain features. The project is split into two main parts: data visualization and exploration, and building a machine learning model.

## Repo Structure
The repository is organized into the following directories and files:
  - **youtube_visualization.ipynb:** Data visualization and exploration of the top 1000 YouTube channels.
  - **youtube_models.ipynb:** Building a machine learning model to predict subscriber growth based on video views, video count, and channel age.
  - data: This folder contains the dataset used in the project, topSubscribed.csv.

## Project Overview

### Libraries used:
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- tensorflow

### 1.Data Visualization and Exploration
Attributes:
- Rank
- YouTube Channel
- Subscribers
- Video Views
- Video Count
- Category
- Started (year the channel was created)

#### Analysis
1. "Music" and "Entertainment" videos receive the most views, making them attractive categories for new content creators.
2. Older channels are more likely to have more combined video views.
3. There is a positive correlation between the number of videos, views, and subscribers. This is supported by the Rank column, which is based on subscriber count.
4. Fewer top YouTube channels are being created each year, according to the Top 1000 dataset.

### 2. Machine Learning Model
Developed a neural network regression model using TensorFlow and Keras to predict subscriber growth based on key metrics.
#### Model Performance:
- Achieved a mean squared error of 45.37, indicating an average prediction error of approximately 6.74 million subscribers.
- Identified a skew in the dataset towards higher subscriber predictions due to its focus on top 1000 channels.
#### Recommendations for Improvement:
- Adjusted model hyperparameters and dataset scaling to potentially enhance accuracy.
- Suggested the inclusion of dummy values and further dataset expansion to better reflect YouTube's diverse channel ecosystem.
#### Implementation:
- Utilized TensorFlow and Keras for model development.
- Preprocessed and scaled dataset for training and evaluation.
#### Future Steps:
- Explore additional features or data sources to improve prediction accuracy.
- Fine-tune model architecture and training parameters based on ongoing evaluation and feedback.


