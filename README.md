# Identifying Data Trends in Housing and Community Development Data of Baltimore, MD. 
## Background Information
Baltimore has seen a steady decline in population in recent years, and numbers continue to drop as residents relocate due to high crime rates (which increased dramatically after the death of Freddie Gray in 2015), lack of economic opportunity, and inadequate education system. The neighborhoods in East and West Baltimore, most of which are predominantly low-income Black and African American communities, are enduring the lasting ramifications of population loss ([source](https://nypost.com/2019/04/19/census-estimates-show-baltimores-population-continues-to-plummet/)). Residents leave these segregated and disadvantaged communities  and with no flow of newcomers to fill their place, vacant properties become areas of criminal and drug activity.   
## Business Question
Before delving into the consequences of the city's failing infrastructure, we must first understand the movement of populations. What relationship exists between population growth and prevalence of vacant properties in low-income neighborhoods, and how we use this information to make informed decisions about the future of housing and community development in Baltimore?
## Data Sources 
1. Population Growth Data: [raw dataset](population_growth.csv) of population percent change from 2010-2015. Pulled from Baltimore Department of Planning [Interactive City Map](https://baltplanning.maps.arcgis.com/apps/webappviewer/index.html?id=d45903fd0a9e4132903920526fcafac7).
1. Vacant Residential Properties Data: [raw dataset](abandoned_housing.csv) of percentages of residential properties that are vacant and abandoned from 2010-2018 categorized by Community Statistical Areas. Pulled from [Baltimore Neighborhood Indicators Alliance](https://vital-signs-bniajfi.hub.arcgis.com/), an open data source that measures indicators of quality of life and health of Baltimore neighborhoods.
1. **exploring-baltimore-development-crisis-kathytien.ipynb**: a Google Colaboratory notebook with data organization and visualization. [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1goyT9-ngpkQ6YYQreq5I2_eODnLVGVb9?usp=sharing)
## Data Answer and Stakeholder Recommendation

![Alt text](scatter_plot.png)

Efforts by the city government to bolster economic activity and population growth have led to the issue of gentrification - cost of living is driven upwards by an influx of investment have displaced the low-income individuals. Thus, 
