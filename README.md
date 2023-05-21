# Earth Observation Intraurban Analysis

[![](https://img.shields.io/badge/OpenSourceLicense-GPL-yellow.svg)](https://opensource.org/license/gpl-3-0/)
[![](https://img.shields.io/badge/Visit-Website-orange)](https://sites.google.com/view/intraurban/home)
[![](https://img.shields.io/badge/Explore-Code-green)](https://code.earthengine.google.com/?accept_repo=users/pinkychow1010/WB_IntraUrban)

## **Introduction**

**Intraurban analysis toolbox** is an interactive API for on-the-fly analysis with Google Earth Engine (GEE), which is a cloud computing platform with a [multi-petabyte catalogue](https://developers.google.com/earth-engine/datasets) of geospatial datasets and satellite imagery. In the recent years, earth observation imagery has become very popular in the global communities to empower diverse environmental applications, including in the domain of **climate risk**. Due to the vast potential, many individuals are keen to extract insights into social and economic factors, such as heat wave exposure or relative wealth. 

[This toolbox](https://sites.google.com/view/intraurban/home) serves as the bridge in between to provide users with derived information about climate hazards **without the need for preprocessing, modelling, and big data storage**. It is intended for scholars worldwide, who would like to explore climate hazards in the urban environment. It is also designed for individuals planning to perform **further analysis and visualization** of the geospatial datasets.

[![](https://github.com/pinkychow1010/pinkychow1010.github.io/blob/master/assets/images/analysis.gif)](https://sites.google.com/view/intraurban/home)

<br>

## **Analysis Task**

The toolbox allow users to easily download analysis-ready data layers, such as urban heat intensity and urbanisation trends within political-administrative boundaries worldwide. Users can download the results in CSV or GeoTIFF format for further GIS analysis.

[![](https://github.com/pinkychow1010/pinkychow1010.github.io/blob/master/assets/images/explore.gif)](https://sites.google.com/view/intraurban/home)

<br>

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

## **Code Catalog**

Below are lists of Javascript code for multiple climate risk analysis. Users can import functions in Google Earth Engine and perform analysis directly using the [API](https://sites.google.com/view/intraurban/home).

<details>
  <summary>Socio-economical Vulnerability 🤒🏙️</summary>
  
  <br>
  
  ![](https://github.com/pinkychow1010/pinkychow1010.github.io/blob/master/assets/images/rwi.gif)
  
  ### Climate Vulnerability
  1. [WorldPop Age Risk](https://github.com/pinkychow1010/EO-Climate-Hazard-Analysis/blob/master/code/age_risk)
  2. [Relative Wealth Index](https://github.com/pinkychow1010/EO-Climate-Hazard-Analysis/blob/master/code/RWI_raster_example)
  3. [Critical Infrastructure](https://github.com/pinkychow1010/EO-Climate-Hazard-Analysis/blob/master/code/critical_infrastructure-spatial-index-cisi)
  4. [Landscan Population](https://github.com/pinkychow1010/EO-Climate-Hazard-Analysis/blob/master/code/landscan_population)
  5. [Drought Index](https://github.com/pinkychow1010/EO-Climate-Hazard-Analysis/blob/master/code/drought_index_pdsi_terraclimate)
</details>

<details>
  <summary>Urban Heat 🥵🏙️</summary>
  
  <br>
  
  ![](https://github.com/pinkychow1010/pinkychow1010.github.io/blob/master/assets/images/lst.gif)
  
  ### Urban Heat Island Analysis
  1. [MODIS-based Land Surface Temperature (LST) Choropleth](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/LST_choropleth)
  2. [MODIS-based Monthly Median LST (2010-2020)](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/LST_monthly)
  3. [LST statitics for land use covers](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/LST_by_LandCover)
  4. [Diurnal LST temperature variation in summers based on Landsat](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/LST_summer)
  5. [UHI Effects Intensity](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/UHI_effects)
  6. [Counting very hot days based on MODIS](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/heatwave_trends)
  7. [Heatwave events time series](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/heatwave_trends)
</details>

<details>
  <summary>Urbanization 👥🏙️</summary>
  
  <br>
  
  ![](https://github.com/pinkychow1010/pinkychow1010.github.io/blob/master/assets/images/density.gif)
  
  ### Population Changes and Urban Development
  1. [Age-based Risk Factor](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/age_risk)
  2. [Analysing Dense Urban Regions](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/extract_urban_centre)
  3. [Analysing Urbanization Changes](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/extract_urbanization_trend)
  4. [Population Count Choropleth](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/population_count_choropleth)
  5. [Population Density Choropleth](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/population_density_choropleth)
</details>

<details>
  <summary>Land Surface Dynamics 🌳🌾</summary>
  
  <br>
  
  ![](https://github.com/pinkychow1010/pinkychow1010.github.io/blob/master/assets/images/lst_lulc.gif)
  
  ### Land Use Changes and Vegetation Dynamics
  1. [Calculate Land Use Proportion](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/calculate_landuse_ratio)
  2. [Evaluating impacts of vegetation changes on LST](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/fvc_ts_func)
</details>

<details>
  <summary>Air Pollution 👥🏭</summary>
  
  ### Air Pollutants and Public Health
  1. ..
</details>

<details>
  <summary>Flooding 🌊🏙️</summary>
  
  ### Flooding History
  1. ..
</details>

<details>
  <summary>Helper 📦</summary>
  
  ### General geospatial functions to aid analysis
  1. [Helper](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/helper)
  2. [Customized Basemap](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/basemap_resources)
  3. [Choropleth Map](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/analysis_utils)
</details>

<details>
  <summary>Interface 💻🖱️</summary>
  
  ### Component to construct API
  1. [App for small raster download](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/raster_downloader)
  2. [Dataset selection](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/raster_downloader_ds_select)
  3. [Resample output](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/code/raster_downloader_res_select)
  4. [Explorer Main Script](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/data_explorer_main)
  5. [Dashboard Functions](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/app_func)
  6. [Admin-boundary-based Analysis Framework](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/app_interface)
  7. [Data Explorer App](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/explorer_interface)
  8. [Data Explorer Functions](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/explorer_utils)
  9. [Data Explorer Dashboard Styling](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/explorer_style)
  10. [Analysis Tool App](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/main_interface)
  11. [Analysis Tool Message](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/main_text)
  12. [Analysis Tool Styling](https://github.com/pinkychow1010/wb-pak-intraurban/blob/master/main_style)
</details>





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

