# DataWrapper DSCoV Workshop

## About

[DataWrapper](https://www.datawrapper.de/) is a free to use online tool for creating interactive visualizations. For inspiration, check out their [River](https://app.datawrapper.de/river), a repository of data visualizations that you can easily adapt.

## Chart Data

In this workshop, we will be using data from the [Rhode Island Department of Health](https://ridoh-drug-overdose-surveillance-fatalities-rihealth.hub.arcgis.com/datasets/rihealth::statewide-rate-of-all-drug-involved-fatal-overdose-by-race-and-ethnicity-and-year/about) on 2017-2023 overdose death rates by race and ethnicity. The data is available below and as a downloadable .csv file within this repository: [od_race_dscov.csv](od_race_dscov.csv)


| Year  | Black or African American| Hispanic or Latino| White|
|------:|-------------------------:|------------------:|-----:|
|2017   |                      38.6|               22.1|  30.2|
|2018   |                      29.8|               18.4|  29.8|
|2019   |                      44.6|               20.3|  27.6|
|2020   |                      51.9|               21.3|    35|
|2021   |                      54.3|               25.6|  37.9|
|2022   |                      53.7|               37.5|  34.7|
|2023   |                      47.9|               31.8|  35.6|

## Map Data

DataWrapper accepts spatial files including GeoJSON. We will use the [map_geometry.geojson](map_geometry.geojson) file to create our basemap and will populate it with [map_data.csv](map_data.csv)