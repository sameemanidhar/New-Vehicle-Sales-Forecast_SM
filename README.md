# New Vehicle Sales Forecast in Canada

The automotive industry is a substantial contributor to the global economy, and accurate forecasting of new motor vehicle sales is fundamental for manufacturers, dealerships, and other stakeholders to make informed business decisions. The purpose of this project is to create a prediction model that accurately predicts new car sales using statistical methodologies and machine learning algorithms. Seasonal demands, monthly gas prices, interest rates, unemployment rates, and natural disasters can gravely impact sales if companies are not aware of the trends and hence prepared for them. Sales forecasting will therefore help companies anticipate market trends, arrange their catalogue, calculate the revenue, and decide on new investments. Another key advantage would be having a predetermined internal target per the data.

## Dataset
The dataset of new motor vehicle sales in Canada from Jan 2000 - Dec 2022 was collected. Other dependencies like mean temperature, precipitation, ground frost days, unemployment rate, employment rate, GDP, GDP - motor industry, gas prices, and cpi of the entire Canada were also collected. Since the vehicle sales dataset was monthly frequency, we had to ensure that the rest of the dependencies were also in monthly frequency from the same range.

The dataset was collected from: 
https://www150.statcan.gc.ca 
https://www.uea.ac.uk/groups-and-centres/climatic-research-unit

## Model Development
The project consisted of 5 models. Multivariate Linear Regression Model, two statistical models: ARIMA & SARIMA and two machine learning models: Decision Tree & Random Forest Regressor.

## Getting Started

### Requirements
- Python 3.6 or higher
- Keras 2.4.3 or higher
- TensorFlow 2.4.1 or higher
- scipy
- matplotlib
- pandas
- scikit-learn
- plotly

- Jupyter Notebook or Google Colab
- Visual Studio Code (or any preferred text editor)

## Results
The provided code demonstrates various techniques to assess and transform time series data for forecasting new vehicle sales. A fully functional interactive dashboard was created and deployed based on these machine-learning models.

### Dashboard 
https://sales-forecasting-dashboard-sm.streamlit.app


![Light1](https://github.com/sameemanidhar/New-Vehicle-Sales-Forecast_SM/assets/153468609/7e445b9a-98b1-42ae-8fd8-dcab6fdc95df)


<span style='font-size: small'>Copyright © 2023 Samee Manidhar. All Rights Reserved.</span>
