# Project-Time-Series-Forecast-Beer-Production
This project aims at forecasting the beer production in megaliters for years 1995-2000 using the historical data

---

# Australian Beer Production Forecast (1996)

## Overview

This project aims to predict the monthly beer production in Australia for the years 1996-2000. While the provided dataset covers several decades from 1956 to 1995, it contains only two columns: Time frame and beer production. It's intuitive to think that multiple factors influence beer production in a country, including temperature, price, advertising, economic and political factors, and more. However, this project primarily focuses on forecasting beer production using the historical data at hand.

The unit of monthly beer production is in megaliters.

## Methodology

To achieve the goal of predicting beer production, this project employed the SARIMAX (Seasonal Autoregressive Integrated Moving Average with Exogenous Regressors) model. This statistical model is commonly used for time series forecasting, allowing us to account for seasonality and other temporal patterns that might impact beer production.

### SARIMAX Model

SARIMAX combines ARIMA (AutoRegressive Integrated Moving Average) with exogenous regressors, allowing us to incorporate external factors into our forecasting model. In a practical sense, this means we can make predictions by considering historical production data along with any additional factors we believe may influence beer production.

## Results

The SARIMAX model was trained on the available dataset, and forecasts were generated for the year 1996. The forecast values for monthly beer production in Australia for the years 1995-09 to 2000 are as follows:

	          Forecast
1995-09-01	129.201730
1995-10-01	164.717849
1995-11-01	190.498579
1995-12-01	180.611712
1996-01-01	150.036754
1996-02-01	138.649104
1996-03-01	148.419637
1996-04-01	136.291654
1996-05-01	145.038382
1996-06-01	119.225425
1996-07-01	133.319343
1996-08-01	138.687390
1996-09-01	130.435667
1996-10-01	172.889229
1996-11-01	181.990136
1996-12-01	181.786655
1997-01-01	152.244477
1997-02-01	136.617234
1997-03-01	146.481100
1997-04-01	140.697603
1997-05-01	138.117874
1997-06-01	119.088996
1997-07-01	135.822438
1997-08-01	134.390670
1997-09-01	133.560464
1997-10-01	169.509651
1997-11-01	171.332673
1997-12-01	183.894687
1998-01-01	148.647043
1998-02-01	133.846982
1998-03-01	150.079997
1998-04-01	141.105383
1998-05-01	128.636869
1998-06-01	122.169779
1998-07-01	133.270201
1998-08-01	133.876571
1998-09-01	136.885463
1998-10-01	160.129298
1998-11-01	169.495371
1998-12-01	184.650552
1999-01-01	141.350342
1999-02-01	131.949531
1999-03-01	153.578572
1999-04-01	135.177633
1999-05-01	126.943275
1999-06-01	124.457053
1999-07-01	126.253276
1999-08-01	137.524013
1999-09-01	135.166138
1999-10-01	153.843010
1999-11-01	177.158305
1999-12-01	181.901088
2000-01-01	137.474124
2000-02-01	131.871581
2000-03-01	151.912753
2000-04-01	128.544292
2000-05-01	133.499525
2000-06-01	122.142023
2000-07-01	121.629207
2000-08-01	139.873329
2000-09-01	129.259091
2000-10-01	156.462143
2000-11-01	184.398451
2000-12-01	177.605366

## Dependencies

pandas
numpy
seaborn
matplotlib
scipy
statsmodels

## How to Run the Code

The .ipynb file in this repository gives the step by step instructions to go ahead with forecasting any similar models.
