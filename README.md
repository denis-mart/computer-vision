# Personal portfolio

Summary of some of my personal work

## 1. Kaggle Petfinder

- **Deep Learning**
- Computer Vision
- Regression
- Goal: Given a pet image an addional metadata -> predict the image social score
- Framework: Pytorch on GPU
- Experiments: 
    * Xgboost (EfficientNet b0 feature extraction + metadata)
    * ConvNet (EfficientNet b0)
    * MLP based on Backbone (EfficientNet b0 + MLP Metadata)
    * MLP based on Backbone (EfficientNet b1 + MLP Metadata)
- Best model: MLP based on Backbone (EfficientNet b2 + MLP Metadata)
    * Kaggle test set RMSE: ~ 19. (best rank: p50 of the leaderboard)

## 2. Time Series Prediction

### Time Serie "1"

- **Machine Learning**
- Regression
- Goal: forecast future values of time series
- Experiments:
- Best model: