# Crypto Market ML Project

This project implements an end-to-end machine learning pipeline on **BTC/USDT daily data**  
(Source: [CryptoDataDownload](https://www.cryptodatadownload.com/cdd/Binance%20BTCUSDT_d.csv)).

## Steps
- Data preprocessing & feature engineering (returns, moving averages, volatility)
- Regression models: Linear, Decision Tree, KNN, SVR, MLPRegressor
- Classification models: Logistic Regression, Decision Tree, KNN, SVC, MLPClassifier
- Clustering: DBSCAN & Agglomerative (evaluated with Silhouette & DBI)
- Metrics: RMSE (regression), Accuracy (classification)

## Results
- Linear models generalized better on noisy financial data
- MLPClassifier achieved the best classification accuracy
- DBSCAN provided the clearest clustering with proper parameter tuning

## Files
- `crypto_ml.ipynb` → main Colab notebook
- `charts/` → output plots
- `data/` → sample dataset

---
⭐ Feel free to fork, explore, and connect with me on [LinkedIn](https://www.linkedin.com/in/pooria-jafari/).
