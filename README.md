Yelp Business Intelligence Platform

Small restaurants and cafes often make staffing, inventory, and operational decisions based on intuition rather than data. Unlike large restaurant chains, they typically lack access to analytics tools that help optimize costs and improve customer satisfaction.
This project uses the Yelp Academic Dataset to provide data-driven insights that help local businesses better understand customer behavior, predict demand, and identify what drives positive reviews.

Restaurants face three common challenges:
- Overstaffing or understaffing, leading to unnecessary labor costs
- Inventory waste from inaccurate demand planning
- Limited understanding of what factors influence customer satisfaction

The goal was to build an affordable analytics solution that helps businesses make smarter operational decisions.

Approach:
1. Customer Traffic Forecasting
Built a forecasting model to predict daily customer traffic using: Prophet, XGBoost
Feature engineering for: Weekly patterns, Seasonal trends, Historical traffic behavior

2. Review Analysis
Developed an NLP pipeline to identify which aspects of the customer experience drive 5-star reviews.
Analyzed mentions of: Food, Service, Ambience, Value, Speed, Results

Traffic Prediction
Ensemble Model: Prophet + XGBoost
Mean Absolute Error (MAE): 1.12 check-ins

Key finding:
Food quality and service were the strongest drivers of 5-star reviews.
Value and speed had a smaller impact on customer satisfaction.
