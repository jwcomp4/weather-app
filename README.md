# From Notebook to Dash App

This repo includes all of the files that explore current and historical weather data and convert that data exploration into a functional, interactive web app using Dash. If you're interested in learning how to transition from a notebook to a Dash app, please feel free to fork this repo and clone for your own exploration. 

Below are a few notes about the files in the repo.

## Jupyter Notebook

This Jupyter Notebook tht explores basic weather data from 2 data sources:

1. [Open-Meteo](https://open-meteo.com/)
2. [Weather API](https://www.weatherapi.com/)

All of the data exploration and API use included in this jupyter notebook require only the free versions of these APIs. Using these resources does require an API key, and the links above will enable you get started there. 

Additionally, these APIs do require geocoded addresses. You can find an excellent resource on geocoding in python here:

[Geocoding in Python](https://towardsdatascience.com/geocode-with-python-161ec1e62b89)

There are many options for geocoding, this project uses the Google Maps API, which will also requires an API key. For more information, please visit this link:

[Google Maps API](https://mapsplatform.google.com/)

The notebook is thoroughly commented throughout with relevant explanations and links.

## The Dash App

Dash is a framework for building data apps in Python. This applications uses some enterprise-level, proprietary packages for some of the layout components. If you're just getting started with Dash, check out the documentation:

[Dash Documentation](https://dash.plotly.com/)

Here is a list of other helpful documentation links for components used in this application

[Dash Core Components](https://dash.plotly.com/dash-core-components)

[Callbacks](https://dash.plotly.com/basic-callbacks)
