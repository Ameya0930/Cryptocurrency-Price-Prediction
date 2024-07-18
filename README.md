# Cryptocurrency Price Prediction with XGBoost

## Overview
This project aims to predict cryptocurrency prices using machine learning techniques, specifically focusing on the XGBoost algorithm. Historical data from Yahoo Finance API is utilized to train and evaluate the model.

## Methodology
- **Data Collection**: Historical cryptocurrency price data for Bitcoin (BTC-USD) was fetched using the Yahoo Finance API.
- **Data Preprocessing**: Data was cleaned, missing values were filled using forward and backward filling, and technical indicators such as EMA (Exponential Moving Average) and MACD (Moving Average Convergence Divergence) were calculated.
- **Model Development**: An XGBoost regressor model was trained on the preprocessed data, with hyperparameters tuned using GridSearchCV for optimal performance.

## Results
- **Performance Metrics**:
  - Training Set:
    - Mean Absolute Error (MAE): X
    - Root Mean Squared Error (RMSE): X
    - R2 Score: X
  - Testing Set:
    - Mean Absolute Error (MAE): X
    - Root Mean Squared Error (RMSE): X
    - R2 Score: X

- **Visualizations**:
  - Actual vs. Predicted Closing Prices Plot
  - Feature Importance Plot

## Discussion
The XGBoost model demonstrated promising results in predicting cryptocurrency prices. The feature importance analysis highlighted the significance of technical indicators like EMA and MACD in making accurate predictions. Challenges included...

## Conclusion
The developed model provides valuable insights for cryptocurrency traders and investors, aiding in decision-making processes. Future work could involve...

## Implementation Details
### Environment Setup
- Python 3.9
- Required Libraries: pandas, numpy, ta, scikit-learn, xgboost, matplotlib
- macOS users: Install `libomp` using `brew install libomp` to resolve XGBoost library loading issues.


