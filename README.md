# TDSP_Project

This Repository is a part of project Hosted by National Big data innovation hub in collabartion with Columbia university. The Goal of the project is find and analyse the major reasons resulting to accidents in major metropolitan cities (Newyork, Chicago etc). The findings have to be perfectly visualized in the form of poster, Which will be reviewd by the National big data innovation hub.

# Project scope

We had taken chicago city as the anchor for the project, each and every analysis involves the [Accidents dataset](https://drive.google.com/file/d/1CVEgeY5URCClgMMtbOYNSj4na9LNVZHL/view?usp=sharing), that we had obtained from the https://data.cityofchicago.org/ portal. The data ranges from 2016-2024 (2013,2014,2015 and 2025 were not considered due to insufficient data). The goal of this project is to analyse the accidents caused by "Worn roads" in the souther chicago and at the end the major findings of the project are made into a one page poster. During the process we also take the liberty in analysing the Time series, weather and lighting. 

# Project Walk through

## Brief overview

The notebook of the analysis can be split into three sections:
* Time series analysis
* Weather and lighting analysis
* Worn surfaces analysis.
For the Time series analysis(TSA) and Weather, Lighting analysis we had taken the full city of chicago as the area to cover and For worn surfaces we took only the souther chicago (Reason can be found out in the notebook and poster).

## Time series analysis.

A Time series analysis(TSA) was peformed on the cleaned data to identify the trends, seasonality and Residual to find the patterns in number of crashes over the days between the years 2016-2024. A noticiable pattern was identifyed and explained in the notes.

## Weather and Lighting analysis

A thorough analysis had been made to identify how Weather annd lighting has impact on the crashes. 
For the people who had gone through the note book:
You can see that the Weather data was normalized, but this was nromalized data was not considered for the weather-lighting heat map. The reason being, the Lighting data cannot be normalized, because we lack the data(How many vehicles at diferent lighting), so using a normalized weather data with a raw lighting data make the analysis meaningless.


## Worn surfaces analysis

For the worn road surface analysis, we had taken only the southern chicago, the reason being, am increase in suspecious amount of accidents due to worn surfaces in the southern part of the city.
Analysis had been made to identify, the streets and neighbourhoods with increased accidents due to worn surfaces, areas with worn surface accidents in 2024 etc.

## Poster

The poster only involved the discoveries made for the worn surfaces accidents, adding tsa and weather, lighting makes the poster have way too much information, confusing the readers and not sticking with the project goal.

![TDSP_Poster](https://github.com/user-attachments/assets/c4c364b5-d11f-403a-9675-0193cd1cd5b0)

