# Visualizing Global CO2 Emissions

## Overview
This project analyzes and visualizes global CO2 emissions using data from "Our World in Data" combined with GeoJSON geographic data. It demonstrates the processing of CO2 emissions data and its integration with geographic information systems (GIS) using GeoPandas and ArcGIS, with a focus on creating dynamic visualizations of annual emissions per country over time. View the interactive map [here](https://tjhsst.maps.arcgis.com/home/item.html?id=f9bfbab3880146649e6f449967cbf0a9).

## Data Sources
- **Annual CO2 Emissions Per Country**: Provided by "Our World in Data", this dataset includes annual CO2 emissions for each country.
- **GeoJSON Data**: Geographic boundaries of countries are sourced from a public [GitHub repository](https://github.com/georgique/world-geojson), facilitating spatial analysis.

## Features
- **Data Processing**: The notebook includes detailed preprocessing steps such as data cleaning, transformation, and the merging of CO2 emissions data with GeoJSON data.
- **Dynamic Visualization**: Utilizes ArcGIS's timeline feature to display changes in emissions over time interactively.

## Installation
To run this notebook, ensure you have the following:
- Python 3.x and Jupyter Notebook
- Required Python libraries: `pandas`, `geopandas`, `arcgis`

```bash
pip install pandas geopandas arcgis
```

## Usage
After cloning the repository, navigate to the directory containing the notebook and launch Jupyter Notebook to execute the analysis.

```bash
git clone https://github.com/yourusername/Visualizing-CO2-Data-With-GeoJson-and-ArcGIS.git
cd Visualizing-CO2-Data-With-GeoJson-and-ArcGIS
jupyter notebook
```

Make sure to replace `https://github.com/yourusername/Visualizing-CO2-Data-With-GeoJson-and-ArcGIS.git` with the actual URL of your GitHub repository. This will guide users on how to properly clone and run your project, as well as how to contribute to it.


