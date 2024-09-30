# **🏡 Real Estate Price Prediction**

**Team Member**
1. Ahmadio Rasyadi Hermanu
2. Rimbi Rodiyana Sova

**📋 Project Overview**

In the dynamic and competitive real estate market, accurately predicting property prices can offer a significant advantage to investors and real estate professionals. This project focuses on leveraging machine learning techniques—specifically XGBoost—to predict property prices in Washington D.C. based on historical data and property features.

**🛠 Tech Stack**
- Language: Python
- Dataset : [DC_Properties.csv](https://www.kaggle.com/datasets/christophercorrea/dc-residential-properties)
- Tableau : [Tableau](https://public.tableau.com/app/profile/rio.sova/viz/WashingtonDCProperties/Dashboard1?publish=yes)
- Machine Learning:
  1. LinearRegression
  2. KNeighborsRegressor
  3. DecisionTreeRegressor
  4. RandomForestRegressor
  5. GradientBoostingRegressor
  6. XGBRegressor
  7. Scikit-learn
- Data: Historical property sales, property features, market trends
- Visualization: Matplotlib, Seaborn, Plotly

**💡 Background**

The real estate market in Washington D.C. presents unique challenges, with property prices affected by a wide range of factors, such as location, property features, and market trends. Traditional methods often fail to capture these complexities, leading to suboptimal pricing strategies.

With the rise of big data and advanced machine learning algorithms, we can now develop more accurate models to predict property prices, empowering businesses to make data-driven decisions and improve profitability.

**🚨 Problem Statement**

Our goal is to develop a machine learning model that improves the accuracy of property price predictions, using XGBoost to account for complex relationships between property features and market trends. By doing so, we aim to provide actionable insights into price forecasting for real estate professionals.

**🎯 Project Goals**

- Develop a Predictive Model: Create a machine learning model using XGBoost to predict property prices.
- Optimize Model Performance: Improve accuracy through hyperparameter tuning and feature engineering.
- Analyze Feature Importance: Identify key factors that drive price variations in the real estate market.
- Evaluate Model: Use error metrics like MAE, MAPE, and R-squared to assess the model’s performance.
  
**⚙️ Analytic Approach**

- Data Preprocessing: Clean and prepare historical sales data and property features (e.g., number of rooms, property location, etc.).
- Feature Engineering: Create new features based on existing data to improve the model's performance.
- Model Selection: Use machine learning models such as XGBoost for regression analysis to predict prices.
- Hyperparameter Tuning: Optimize the XGBoost model by adjusting hyperparameters for the best performance.
- Model Evaluation: Assess the performance of the model using metrics like RMSE (Root Mean Squared Error) and compare with baseline models like linear regression.


**📊 Results**

Metric	Value
- MAE	47,075.65
- MAPE	11.36%
- R-squared	0.7294
- RMSE	71,061.60
The XGBoost model successfully predicts property prices with a relatively high degree of accuracy, explaining approximately 72.94% of the variance in prices. However, some room for improvement remains, as shown by the MAPE and RMSE values.

**🔍 Limitations**

1. Dynamic Market Conditions: While the model can predict prices based on historical data, it may not always be able to capture sudden shifts in the market, such as changes due to unforeseen events (e.g., political shifts, economic crises, natural disasters).
2. Overfitting Risk: Despite XGBoost’s ability to handle overfitting through regularization techniques, there is always the possibility that the model could be too closely tuned to the training data, resulting in poorer performance when exposed to unseen data or in changing market conditions.
3. Limited Scope of Features: The current model may not account for some unquantifiable or difficult-to-measure factors such as future urban development plans, sentiment in the market, or speculative investments, all of which can influence property prices.
4. Computational Complexity: XGBoost, while powerful, can be computationally expensive, especially when dealing with large datasets or performing hyperparameter tuning. This may limit its deployment in real-time pricing systems without proper infrastructure.

**🔧 Recommendations**

1. Integrate the Model into Decision-Making Processes: The XGBoost model should be incorporated into the company's pricing strategies. Regularly updating the model with fresh market data will ensure it remains relevant and accurate, enabling the company to stay ahead of pricing trends and market shifts.
2. Expand Feature Set: While the current model focuses on property features and historical sales data, additional factors such as economic indicators (e.g., interest rates, inflation) and neighborhood growth trends can be included to improve predictive accuracy.
3. Regular Model Retraining: The real estate market is constantly changing. It’s crucial to retrain the model regularly, at least quarterly or after any major shifts in the market (e.g., new regulations, economic downturns), to ensure it continues to provide accurate price predictions.
