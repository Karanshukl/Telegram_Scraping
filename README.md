# CapX

This project focuses on scraping messages from Telegram channels to extract stock market-related insights and build a predictive model for stock price movements. It includes data scraping, preprocessing, feature extraction, machine learning model training, and evaluation.

## Features
- Telegram Data Scraper:- Uses the Telethon library to scrape Telegram messages from specified channels.
- Data Preprocessing:- Cleans and processes raw text data for feature extraction.
- Feature Engineering:- Extracts features relevant to stock market prediction, such as sentiment scores and keywords.
- Prediction Model:- Implements a machine learning model to predict stock movements.
- Evaluation Metrics:- Assesses model performance using metrics like accuracy, precision, recall, and F1-score.


## Modeling

Several machine learning models were tested and evaluated, including:

- Linear Regression: A basic linear approach to understand feature relationships.
- Random Forest Regressor: A tree-based ensemble model to capture non-linear relationships.
- Gradient Boosting Regressor: A boosting method that typically offers strong performance.
- XGBoost Regressor: A highly optimized and scalable model that provides state-of-the-art results for tabular data.
Evaluation metrics used:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
Hyperparameter tuning was conducted using cross-validation to improve model performance.

## Requirements

To run this project, install the dependencies in [requirements.txt](https://github.com/Karanshukl/capX/blob/main/requirements.txt)

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- xgboost
- nltk


## Future Improvements

- Integrate additional data sources (e.g., news websites, stock APIs).
- Explore deep learning models for improved prediction accuracy.


## Links 🔗
🔗 Github [karanshukl](https://www.github.com/karanshukl)  
🔗 Linkedin - [karanshukl](https://www.linkedin.com/in/karanshukl/)

Follow for more details :- [@karanshukl](https://www.linkedin.com/in/gkaranshukl/)
