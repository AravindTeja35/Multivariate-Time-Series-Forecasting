# Multivariate Time Series Forecasting: ​Evaluating Price Prediction of Cryptocurrencies (LSTM Modelling)

**Introduction**

This project aims to predict Bitcoin returns for a 15-minutes from present period in isolation and when combined with other major cryptocurrencies like Ethereum and Cardano. Through exploratory data analysis, data preprocessing, and employing LSTM models, we explore the intricacies of cryptocurrency price movements and attempt to forecast Bitcoin's short-term returns.

**Objective**

The primary objective is to forecast cryptocurrency's 15-minute returns from present period using:

- Bitcoin data in isolation.
- A combination of Bitcoin + Ethereum data.
- A combination of Bitcoin + Ethereum + Cardano data
This endeavor seeks to understand the impact of incorporating multiple cryptocurrencies on the accuracy of Bitcoin return predictions.

**Approach**

![image](https://github.com/AravindTeja35/Multivariate-Time-Series-Forecasting/assets/163460197/fd0b82d1-90c5-4520-9274-f8b1ac313c69)

**Dataset Description**

Our analysis is based on a comprehensive dataset that includes:
![image](https://github.com/AravindTeja35/Multivariate-Time-Series-Forecasting/assets/163460197/35ae7f57-3ae8-45ca-a8e3-808c3a65db0d)

**Methodology**

Our methodology follows as:

- Exploratory Data Analysis (EDA): Analyzed null values, gaps, and distributions. Identified correlations among cryptocurrencies.<br />
- Data Preprocessing: Included null value imputation, gap filling, log transformations, and feature engineering.<br />
- Modelling: Utilized LSTM models to forecast cryptocurrency's 15-minute returns. The models were evaluated based on Mean Squared Error (MSE) and Mean Absolute Error (MAE) metrics.

Three LSTM models were developed:

- Model 1: Bitcoin
- Model 2: Bitcoin + Ethereum
- Model 3: Bitcoin + Ethereum + Cardano.

**Conclusion**

![image](https://github.com/AravindTeja35/Multivariate-Time-Series-Forecasting/assets/163460197/fb224e06-0437-4a62-9b1a-2e020595d53a)

Among all the three models, the model with three different crypto assets (Bitcoin + Ethereum + Cardano) has performed well compared to the other two models due to diversified nature of data. Additionally, our project illustrates the potential of LSTM models in forecasting cryptocurrency returns. By incorporating data from multiple cryptocurrencies, we achieve better prediction accuracy, highlighting the interconnectedness of the cryptocurrency market.
