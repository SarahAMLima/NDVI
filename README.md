# NDVI Web Map Project - Vesuvius National Park

This repository hosts an interactive web map displaying NDVI (Normalized Difference Vegetation Index) layers for Vesuvius National Park, highlighting vegetation health trends over time, particularly in response to wildfires in 2017.

## Project Background
Vesuvius National Park has experienced significant wildfires in recent years, impacting its forest cover and vegetation health. This NDVI map project is designed to assess vegetation recovery and monitor areas at risk, using satellite data to visualize the effects of environmental disturbances on the park’s ecosystem.

## Features
- **Interactive NDVI Layers**: Toggle between years to observe vegetation changes, with a focus on post-fire recovery.
- **Color-coded Legend**: Easily interpret vegetation health, from low to dense vegetation cover.
- Singleband pseudocolor color ramp with the same intervals for all layers allow a direct comparison, the colors meaning:  
       Dark Red for lower NDVI values (-0.09) to represent bare or sparse vegetation.
       Yellow/Orange for moderate NDVI values (0.0) for mixed or sparse vegetation.
       Green for high NDVI values (0.6) to represent healthy, dense vegetation.

## Technologies Used
- **QGIS & qgis2web**: For NDVI calculations and web map generation.
- **Leaflet/OpenLayers**: JavaScript libraries for interactive map display.
- **GitHub Pages**: Public hosting for open-access viewing.

## Expected Outcomes
This map aims to provide insights into how vegetation recovers over time post-wildfire. By monitoring NDVI trends, users can assess the effectiveness of natural regeneration and identify zones requiring restoration.

## How to Access the Map
Visit the published web map [here](https://sarahamlima.github.io/NDVI/) to explore vegetation changes interactively.

## Data Sources
- **Satellite Imagery**: Sentinel-2 L2 for 1990, Landsat-8 L-2 for 2017, with NDVI processed to visualize vegetation.
- **Tools**: QGIS, Python for data automation, and GitHub Pages for hosting.
