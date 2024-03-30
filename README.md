# lstm-portfolio-optimization

Portfolio optimization is a crucial task for investors seeking to maximize returns while managing risk. This project leverages deep learning techniques, specifically LSTM models, to forecast stock prices of selected Moroccan companies (Attijariwafa bank (AWB), Maroc Telecom (IAM), Bourse de Casablanca (BC), Société Générale des Travaux du Maroc (SGTM), Managem (MAN)). The historical stock data is retrieved from Yahoo Finance and preprocessed to handle missing values, outliers, and standardize the data.



The repository includes Jupyter Notebooks with detailed explanations, code, and visualizations for data retrieval, preprocessing, model training, evaluation, and visualization. Specifically, it covers:

1- Data Retrieval: Code to fetch historical stock data from Yahoo Finance for selected Moroccan companies.

2-Data Preprocessing: Techniques for handling missing values using forward-fill imputation, handling outliers using the Interquartile Range (IQR) method, and standardizing the data are implemented as part of data preprocessing.

3- Exploratory Data Analysis (EDA): Visualizations and analysis of stock returns, correlation matrices, and pairplots are conducted to gain insights into the data.

4- LSTM Model Training: Definition and training of LSTM models for each asset, including data preparation, model definition, training loop, and evaluation.

5- Evaluation and Visualization: Evaluation of model performance using various metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE), and Mean Percentage Error (MPE) and visualization of true vs. predicted values for each asset.

6- Model Saving: The trained PyTorch LSTM model is saved for future use, ensuring easy deployment and inference.



The trained LSTM models are utilized to predict future stock prices, and portfolio optimization strategies are applied based on these predictions. The project aims to provide insights into using advanced machine learning techniques for portfolio management and investment decision-making.
