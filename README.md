# bitcoin_prediction

This repository contains code for analyzing and predicting Bitcoin price movements based on sentiment analysis of Wikipedia edit comments and integrating financial data from Yahoo Finance. The project leverages machine learning and deep learning techniques to establish correlations and predict future Bitcoin prices.

## Usage

The main scripts are structured to fetch data, process it, and perform predictions as follows:

1. Fetching Wikipedia Data: This script uses mwclient to fetch the history of Wikipedia edits on the Bitcoin page.

2. Sentiment Analysis: Utilizes transformers for sentiment analysis on edit comments to gauge the general sentiment over time.

3. Data Preparation: Structures the sentiment and edit data into a usable format for time-series analysis.

4. Financial Data Integration: Fetches historical Bitcoin prices from Yahoo Finance and merges them with Wikipedia edit data.

5. Machine Learning Prediction: Employs models like Random Forest and XGBoost to predict future price movements based on historical data.

6. Deep Learning Model: Utilizes TensorFlow to build and train a deep neural network for prediction, improving accuracy and precision.

## Models Used

1. Random Forest Classifier
2. XGBoost Classifier
3. Deep Learning Models with TensorFlow
4. Evaluation

The models are evaluated based on precision scores, and predictions are backtested to ensure robustness. Based on the evaluation it is clear that the models perform based on a little more than 50% accuracy which is still not enough to base your investments on the models.

## Potential Improvements and Considerations
1. Model Enhancements: Explore more advanced NLP techniques for sentiment analysis to improve accuracy, such as fine-tuning transformers on a domain-specific corpus (financial texts).
2. Feature Expansion: Incorporate additional data sources like news articles, social media sentiment, or macroeconomic indicators that might impact Bitcoin prices.
3. Model Complexity: While deep learning models offer potential, they require careful tuning and validation to prevent overfitting, especially with time-series data.
4. Real-time Application: For real-world applications, consider developing a pipeline that automatically updates data, re-trains the model periodically, and adjusts to new patterns in data.

## Contributing

Contributions to this project are welcome! Please fork the repository and submit pull requests with your proposed changes.
