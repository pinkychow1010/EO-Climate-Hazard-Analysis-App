# Earth Observation Intraurban Analysis

[![](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![](https://img.shields.io/badge/Open-Website-orange)](https://sites.google.com/view/intraurban/home)
[![](https://img.shields.io/badge/Explore-Code-green)](https://code.earthengine.google.com/?accept_repo=users/pinkychow1010/WB_IntraUrban)

## **Introduction**

Intraurban analysis toolbox is an interactive API for on-the-fly analysis with Google Earth Engine (GEE), which is a cloud computing platform with a [multi-petabyte catalogue](https://developers.google.com/earth-engine/datasets) of geospatial datasets and satellite imagery.  In the recent years, earth observation imagery has become very popular in the global communities to empower diverse environmental applications, including in the domain of climate risk. Due to the vast potential, many individuals are keen to extract insights into social and economic factors, such as heat wave exposure or relative wealth. [This toolbox](https://sites.google.com/view/intraurban/home) serves as the bridge in between to provide users with derived information without the need for preprocessing, modelling, and big data storage. It is intended for scholars worldwide, who would like to explore climate hazards in the urban environment. It is also designed for individuals planning to perform further analysis and visualization of the geospatial datasets.

![](https://github.com/pinkychow1010/pinkychow1010.github.io/blob/master/assets/images/analysis.gif)

<br>

## **Analysis Task**

The toolbox allow users to easily download analysis-ready data layers, such as urban heat intensity and urbanisation trends within political-administrative boundaries worldwide. Users can download the results in CSV or GeoTIFF format for further GIS analysis.


* **Heatwave Tracking**

How did historical heatwaves spatial distributed? What are the long term trends in their frequency, intensity and duration?

* **Urban Heat Island Effects**

How is urban heat spatially distributed? Which neighborhood has more intense UHI effects?

* **Land surface temperature time series for vegetation change hotspots**

Are there relationship between urban heat and changes of urban green?

* **Age Risk Factor**

Senior population suffers more from heat waves. What are the risk factor for different cities and neighborhoods?

* **Land Cover Ratio**

How do different land cover type spatially distributed? What are the most dominent land uses?

* **Population / Urban Density**

Where do the majority of the population live in the city?

<br>

## **Features**

Below is a partial list of features available for the toolbox. This toolbox is currently under development and more features will be available soon.

* Download landuse cover for any global administrative boundaries (level 2) in customized resolution up to 10m
* Download smoothed daily land surface temperature (.csv) derived from MODIS for global administrative boundaries
* Address UHI hotspots for global administrative boundaries
* Locate vegetation change hotspots for global administrative boundaries
* Download urban and population density map for global administrative boundaries

<br>

## **References**

Gorelick, N., Hancher, M., Dixon, M., Ilyushchenko, S., Thau, D., & Moore, R. (2017). Google Earth Engine: Planetary-scale geospatial analysis for everyone.

World Bank Group. 2022. Pakistan Country Climate and Development Report. CCDR Series;. © World Bank, Washington, DC. http://hdl.handle.net/10986/38277 License: CC BY-NC-ND.