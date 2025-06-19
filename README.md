# Jerusalem Public Shelters Dataset (June 2025 - Non-Official)

![alt text](images/cover.png)

[![View Interactive Map](https://img.shields.io/badge/View-Interactive%20Map-blue?style=for-the-badge&logo=arcgis)](https://www.arcgis.com/apps/instant/sidebar/index.html?appid=6771ca80d88d4f58bde24226cb61f52a)

## ⚠️ Disclaimer ⚠️
While efforts have been made to ensure accuracy, this dataset should not be considered an official source. In emergency situations, always follow instructions from local authorities.

## Overview
This repository contains a list of public shelters in Jerusalem, Israel. The data was collected on June 19, 2025, from the Jerusalem Municipality's public records. This information is being shared to help those in need locate safe shelter during emergencies and to contribute to various mapping and emergency response tools.

## Available Formats

The data is available in multiple formats for different use cases:

| Format | File | Description |
|--------|------|-------------|
| 📍 GeoJSON | [public-shelters-jerusalem_190625.geojson](/public-shelters-jerusalem_190625.geojson) | Geographic data format compatible with most mapping applications |
| 📊 CSV | [converted_formats/jerusalem_shelters_190625.csv](/converted_formats/jerusalem_shelters_190625.csv) | Simple tabular format for spreadsheet applications |
| 🗺️ Shapefile | [converted_formats/jerusalem_shelters_190625.shp](/converted_formats/jerusalem_shelters_190625.shp) | Standard GIS format (includes .dbf, .shx, .prj files) |
| 🌐 GML | [converted_formats/jerusalem_shelters_190625.gml](/converted_formats/jerusalem_shelters_190625.gml) | Geography Markup Language format |
| 📦 GeoPackage | [converted_formats/jerusalem_shelters_190625.gpkg](/converted_formats/jerusalem_shelters_190625.gpkg) | OGC GeoPackage format |
| 🗺️ ArcGIS | [Interactive ArcGIS Map](https://www.arcgis.com/apps/instant/sidebar/index.html?appid=6771ca80d88d4f58bde24226cb61f52a) | Interactive map for easy online viewing |

## Map Screenshots

### Map View
![Map View](/screenshots/1.png)

### Detail View
![Detail View](/screenshots/2.png)

### Legend
![Legend](/screenshots/legend.png)

## Data Modifications

The following modifications were made to the original dataset from the Jerusalem Municipality:

- Original categorisation replaced with a simple 1, 2, 3 system (shelters, car parks, schools with sheltering places)
- Unpopulated fields removed  
- Geolocations and addresses preserved  
- A "full address" field was added which appends ", Jerusalem, Israel" to the local location names to facilitate accessing the locations in geonavigation apps



## Mobile Installation Instructions

For the best mobile experience, we recommend using Hermit to create a lite app:

1. Download [Hermit - Lite Apps Browser](https://play.google.com/store/apps/details?id=com.chimbori.hermitcrab&hl=en) from the Google Play Store
2. Open Hermit and create a new lite app using the ArcGIS map URL
3. Make sure to grant location permissions to the app for optimal functionality
4. Add the lite app to your home screen for quick access during emergencies

## License
This data is shared under an open license to promote public safety and welfare.

## Last Updated
June 19, 2025
