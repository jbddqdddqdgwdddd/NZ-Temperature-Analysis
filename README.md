# NZ-Temperature-Analysis
This repo stores the individual analysis project of STATS 769: Advanced Data Science Practice

The purpose of this lab is to get experience downloading datasets from APIs and working with structured data formats.

For this lab you can use any machine that has R, all necessary packages and `curl`. It is recommended to run it on the Uoa VMs.

## The Data Set

[OpenMeteo.com](https://open-meteo.com/) provides an API for access to both historical weather data as well as weather predictions. 

The values are based on an aggregation of data from worldwide weather stations and creating a world-wide grid of estimates (on land at 0.25 latitude/longitude interval) called [ERA5](https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-single-levels).

The goal is to download daily low/high temperature for Auckland between 1 January 1980 and 30 June 2023. 

Visit the historical API decription page: https://open-meteo.com/en/docs/historical-weather-api and construct a URL that includes the desired data. 

You will need to set the parameters `latitude`, `longitude`, `daily`, `timezone`, `start_date` and `end_date`. You should use the time zone `"Pacific/Auckland"`.
