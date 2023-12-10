# DSF

## Introduction

This project aimed to create different models to predict incidence values of flu like diseases in Swiss regions. Specifically, we focused on Time Series Models, Neural Networks, and Random Forests.

The notebooks below show the creation of different models, as well as the preparation and exploration of our starting data.

To view the notebooks in the correct order, one would start with the google notebooks, the population data notebook, the exploration notebook as well as the weather cleaning notebook. This is where the data is being prepared.

Next, one would view the model notebooks, which are the three random forest notebooks, the arima_sarima notebook as well as the ffn_model notebooks.

To view the data, refer to the data folder.

### Notebooks

| Name                                | Description                                                                                                                              |
| ----------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Random_Forest_Autoregressive.ipynb  | Random Forest Model, with autoregressive prediction of incValue                                                                          |
| Weather_cleaning_copy.ipynb         | Data preparation and cleaning of weather data                                                                                            |
| arima*sarima*.ipynb                 | ARIMA, SARIMA, and SARIMAX Models                                                                                                        |
| exploration.ipynb                   | Some data exploration of Sentinella data                                                                                                 |
| ffn_google_forecast.ipynb           | FFN including exogenous google data                                                                                                      |
| ffn_model.ipynb                     | Base FFN Model                                                                                                                           |
| ffn_model_exogenous.ipynb           | FFN including exogenous data                                                                                                             |
| ffn_model_v2.ipynb                  | Base FFN Model                                                                                                                           |
| google_notebook_grippe.ipynb        | Data preparation and cleaning of google trends of symptoms                                                                               |
| google_notebook_husten_fieber.ipynb | Data preparation and cleaning of google trends of flu and influenza                                                                      |
| helpers.py                          | Helper functions                                                                                                                         |
| naive_forecast_base.ipynb           | Naive forecast / base model                                                                                                              |
| population_data.ipynb               | Data preparation and cleaning of population data                                                                                         |
| random_forest_1y_lags.ipynb         | Random Forest Model variations with 1 year lags                                                                                          |
| random_forest_exogenous.ipynb       | Random Forest Model variations with autoregressive prediction of incValue and Google Grippe trends, as well as combination with 1 y lags |
| requirements.txt                    | Requirements for creating a virtual environment                                                                                          |
| archive                             | Archive of notebooks                                                                                                                     |
| week_dict                           | Week dictionary for consistent coding                                                                                                    |
| date_dict                           | Date dictionary for consistent coding                                                                                                    |

### Data

| Name                 | Description                                    |
| -------------------- | ---------------------------------------------- |
| cv_results           | Prediction of Flu Cases after Cross Validation |
| google_search_trend  | Google Trends Data                             |
| INFLUENZA_oblig      | Influenza Data from BAG                        |
| INFLUENZA_sentinella | Influenza Data from BAG                        |
| pop_data_cantons     | Cantonal Population Data                       |
| scraper              | Data scraping scripts                          |
| weather              | Weather Data from Jan 2013 - Jun 2023          |
| weather_addition     | Weather Data from Jun 2023 - Dec 2023          |
