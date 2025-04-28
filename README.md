##Cryptocurrency Temporal Structure Analysis and Clustering

##Overview

This project aims to perform a comprehensive Temporal Structure Analysis, Clustering, and Exploratory Data Analysis (EDA) on 30 cryptocurrencies.
It follows a structured approach involving data collection, grouping, correlation analysis, and deep temporal exploration of selected cryptocurrencies, forming a foundation for predictive modeling and trading signal generation (in upcoming stages).

The project is divided into 7 main steps, of which the first 4 are completed.

Completed Tasks

1. Data Collection
Downloaded historical price data for 30 cryptocurrencies (minimum 1 year) using online financial data providers like Yahoo Finance.

Data was gathered programmatically for future live-streaming and dynamic analysis.

2. Grouping & Clustering
Dimensionality Reduction: Applied PCA (Principal Component Analysis) to reduce the high-dimensional (365 days) data into fewer meaningful components.

Clustering: Used multiple clustering algorithms (e.g., K-Means, DBSCAN) to group cryptocurrencies into 4 distinct groups.

Selection: Selected one representative cryptocurrency per group for further analysis.

3. Correlation Analysis
Identified and presented the Top 4 Highly Correlated (both positive and negative) cryptocurrencies for each selected cryptocurrency.

4. Exploratory Data Analysis (EDA)
Performed EDA to:

Explore temporal structures.

Visualize the distribution of prices.

Investigate distribution changes across different time intervals.

Provided additional insightful visualizations for deeper understanding.
Upcoming Tasks (Work in Progress)
Step 5: Machine Learning Models
Develop predictive models (e.g., ARIMA, LSTM, Hybrid LSTM+ARIMA, Prophet) for price forecasting.

Step 6: Trading Signal Generation
Generate buy/sell signals based on forecasts and predictive analytics.

Step 7: GUI Development
Create an interactive Graphical User Interface (GUI) to:

Perform EDA

Visualize correlations

Predict future prices

Generate and display trading signals

Technologies Used
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, TensorFlow, Keras)

Yahoo Finance API

Clustering algorithms (K-Means, DBSCAN)

Dimensionality Reduction (PCA)

Machine Learning (for next steps)

Streamlit (GUI — coming soon)

