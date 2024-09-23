# Machine-learning-on-stock-prediction
Stock prediction though machine learning models 
Project Description
Developed a comprehensive stock price prediction model for Tata Consultancy Services (TCS) using Long Short-Term Memory (LSTM) neural networks. The project involved several key steps:

Data Collection: Utilized the Yahoo Finance API to gather historical stock price data from January 2019 to January 2022, including daily Open, High, Low, Close prices, and Volume.

Data Preprocessing: Conducted data cleaning by checking for missing values and employing forward fill techniques to ensure continuity in the dataset. Implemented normalization to scale the data, preparing it for machine learning.

Feature Engineering: Created several technical indicators, including:

Moving Averages: Calculated 50-day and 200-day moving averages to identify trends.
Relative Strength Index (RSI): Computed the RSI to gauge momentum and identify overbought or oversold conditions.
Moving Average Convergence Divergence (MACD): Developed the MACD and signal line to highlight potential buy/sell signals.
Model Development: Built a sequential LSTM model with multiple layers, including dropout layers to prevent overfitting. Trained the model using 80% of the dataset, optimizing it with the Adam optimizer to minimize loss.

Prediction and Visualization: Made predictions on the test dataset and compared them with actual prices. Visualized the historical closing prices, moving averages, and predicted prices using Matplotlib to facilitate analysis and understanding of the model's performance.

Insights and Implications: Analyzed the results to draw actionable insights for investment strategies, emphasizing the importance of technical indicators in predicting stock trends.

This project not only enhanced my understanding of time series forecasting and neural networks but also provided practical experience in data handling and model evaluation in a financial context.
