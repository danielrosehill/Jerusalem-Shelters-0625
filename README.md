# Jerusalem Public Shelters Dataset

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
| 🗺️ Google Maps | [Interactive Google Map](https://www.google.com/maps/d/edit?mid=1BW0i9j2aRLDYirNUZkp83HZVdF3NzPA&usp=sharing) | Interactive map for easy online viewing |

## Data Modifications

The following modifications were made to the original dataset from the Jerusalem Municipality:

- Original categorisation replaced with a simple 1, 2, 3 system (shelters, car parks, schools with sheltering places)
- Unpopulated fields removed  
- Geolocations and addresses preserved  
- A "full address" field was added which appends ", Jerusalem, Israel" to the local location names to facilitate accessing the locations in geonavigation apps

## Disclaimer
While efforts have been made to ensure accuracy, this dataset should not be considered an official source. In emergency situations, always follow instructions from local authorities.

## License
This data is shared under an open license to promote public safety and welfare.

## Last Updated
June 19, 2025
