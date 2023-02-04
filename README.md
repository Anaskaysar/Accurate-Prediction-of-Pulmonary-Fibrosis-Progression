# Accurate Prediction of Pulmonary Fibrosis Progression Using EfficientNet and Quantile Regression: A High-performing Approach

## Predict lung function decline (FVC Measurements)

## Motivation:

The main goal of this project is to propose a network to use EfficientNet, a state-of-the-art convolutional neural network (CNN) architecture and quantile regression (QR) to predict the progression of PF in patients, using the OSIC dataset [5] available on Kaggle.

## objective

- Utilizing the OSIC dataset,
- Combining EfficientNet and QR
- Evaluating the performance of our models using the modified Laplace-Log-Likelihood metric
- Reporting the best score of our model in terms of the modified Laplace-Log-Likelihood (-6.64) which is higher than the existing literature.

## Your Evaluation Metric

For each true FVC measurement, you will predict both an FVC and a confidence measure (standard deviation σ). The metric is computed as:
![scores](./Images/scores.jpg)
