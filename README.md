elp Business Intelligence Platform
Traffic Forecasting & Customer Review Analytics for Small Restaurants
Problem
Small restaurants and cafes often make staffing, inventory, and operational decisions based on intuition rather than data. Without access to the analytics resources used by large chains, they face challenges such as overstaffing, inventory waste, and limited insight into what drives customer satisfaction.
Approach
Analyzed the Yelp Academic Dataset, leveraging 10,000 businesses and 468,000+ reviews to develop predictive analytics tools for local food businesses. Engineered features capturing weekly seasonality, long-term demand trends, and customer sentiment across key categories including food quality, service, ambiance, value, and speed.
Solution
Built an ensemble forecasting model (Prophet + XGBoost) to predict daily customer traffic with 1.12 MAE, enabling data-driven staffing and inventory planning.
Developed an NLP-based review classification model achieving 90% accuracy and 92% precision in identifying the primary drivers of 5-star reviews.
Performed aspect-based sentiment analysis to quantify the impact of food, service, ambiance, value, and speed on customer satisfaction.
Results
The platform helps small businesses:
Optimize staffing schedules based on predicted customer demand.
Reduce inventory waste through more accurate traffic forecasting.
Improve customer satisfaction by prioritizing factors most associated with positive reviews.
Analysis revealed that food quality and service were the strongest predictors of 5-star ratings, while value and speed played secondary roles. By transforming Yelp data into actionable business insights, the project provides small businesses with analytics capabilities typically available only to larger restaurant chains.
Skills Used
Python, Pandas, NumPy, Scikit-learn, XGBoost, Prophet, NLP, Sentiment Analysis, Feature Engineering, Time Series Forecasting, Data Visualization, Predictive Modeling, Machine Learning
