[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SachinRamki/Seafood-Trade-Analysis/blob/main/FAO_Seafood_Analysis.ipynb)

# Seafood Trade Analysis and Forecasting

## Overview

This project aims to provide insights into the global seafood trade industry by conducting an in-depth Exploratory Data Analysis (EDA) and implementing time series forecasting using ARIMA (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal ARIMA) models. The dataset used for this analysis is sourced from the Food and Agricultural Organization (FAO) of the United Nations, which offers comprehensive information on seafood trade spanning multiple years and countries.

The primary objectives of this project are as follows:

1. **Data Preprocessing:** Clean and structure the dataset, making it suitable for analysis and modeling.

2. **Exploratory Data Analysis (EDA):** Gain a deep understanding of the data by visualizing and summarizing key information. This includes investigating global trade by quantity, examining trade volumes by continent and country, and exploring specific products traded by various countries.

3. **Time Series Modeling:** Utilize the ARIMA (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal ARIMA) algorithms to model and forecast the trade volume of fishery and aquaculture products. This involves determining the best model parameters, assessing stationarity, and evaluating model performance.

4. **Interactive Widgets:** Enhance the user experience with interactive widgets that allow you to select specific continents, years, and trade modes for analysis and visualization.


## Dataset

The dataset used in this project contains historical data on various aspects of seafood trade, including imports, exports, production, and consumption, segmented by different countries and seafood categories. It includes factors such as quantities, values, and price indices. This rich dataset serves as the foundation for our analysis and forecasting.
- From [FAO's website][fao], we can customize and generate dataset as per our requirement.

### 1. Data Preprocessing

In this section, the dataset is read and cleaned to remove unnecessary columns and ensure it is ready for analysis. Data filtering is performed based on trade mode (exports/imports).

### 2. Exploratory Data Analysis (EDA)

This section focuses on visualizing and summarizing the data to extract valuable insights. Key features of this section include:
- Visualizing global trade volumes by quantity.
- Analyzing trade volumes by continent and year.
- Exploring specific products traded by individual countries.
- Seasonal trends and patterns in seafood trade.
- Top seafood-producing and consuming countries.
- Interactive widgets to select continents, years, and trade modes for analysis.

### 3. ARIMA Modeling

The AutoRegressive Integrated Moving Average (ARIMA) algorithm is used for time series modeling. This section covers the following:
- Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) analysis.
- Differencing to achieve stationarity.
- Evaluation of the Akaike Information Criterion (AIC) for model selection.
- Augmented Dickey-Fuller (ADF) test for stationarity.

### 4. SARIMA Modeling

The Seasonal ARIMA (SARIMA) algorithm is employed for more accurate modeling and forecasting. This section includes the following steps:
- Selection of the best SARIMA model parameters through a grid search.
- Fitting the SARIMA model to the training data.
- Forecasting on both the test data and future years.
- Visualization of forecasted values and prediction intervals.

### 5. Feature Engineering

This section generates additional features by introducing lagged values and moving averages. These features can enhance the modeling process.

## Execution and Customization

- You can select the continent, year, and trade mode using interactive widgets to customize your analysis.
- Customization of data sources and target countries is possible, allowing for versatile exploration and modeling.
- The code provides detailed explanations and visualizations, making it accessible for both data enthusiasts and professionals.

## How to Use This Repository

This GitHub repository contains Jupyter notebooks that detail the EDA and forecasting process. You can explore the Python code, visualizations, and results in the respective notebooks.

Feel free to use, adapt, or extend the code for your own analysis or research. If you find this work helpful, please consider citing this repository.

## License

This project is open-source and is available under the [MIT License][MIT]. Please review the license for more information on how you can use and share this work.

---
[//]: 

   [fao]: <https://www.fao.org/fishery/statistics-query/en/homer>
   [MIT]: <https://github.com/SachinRamki/Seafood-Trade-Analysis/blob/main/LICENSE>
