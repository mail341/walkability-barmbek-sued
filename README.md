# Walkability_Barmbek_Sued_Hamburg

## Walkability Analysis of Barmbek-Süd (Hamburg)

## Project Overview

This capstone project aims to develop a custom walkability score for the district of Barmbek-Süd in Hamburg, Germany. The analysis combines geospatial, demographic, socio-economic, infrastructure, and mobility data to evaluate how walkable the neighborhood is and how it has evolved over time.

Additionally, the project explores the impact of modern urban services such as ride-pooling (MOIA) and grocery delivery (REWE) on perceived walkability.

## Objectives

- Build a data-driven walkability score  
- Analyze changes from 2013 to 2024  
- Investigate relationships between infrastructure and mobility behavior  
- Evaluate the role of new urban services in walkability  

## Concept of Walkability

Walkability is modeled using three dimensions:

### Infrastructure
- Street network and road types  
- Pedestrian crossings  
- Traffic lights  

### Accessibility
- Public transport connections  
- Mobility hubs (e.g. switch points, bike stations)  

### Environment
- Green spaces and parks  
- Quiet areas  

## Data Sources

- Hamburg district statistics (2013–2024)  
- Hamburg Geoportal (infrastructure and spatial data)  
- OpenStreetMap (points of interest, street network)  
- Mobility services (MOIA, switch points)  
- Delivery services (REWE)  
- Additional infrastructure data (e.g. schools, healthcare)  
- Hamburg Masterportal-API

## Methodology

1. Data collection and cleaning  
2. Spatial filtering to Barmbek-Süd using GeoPandas  
3. Feature engineering (e.g. population density, infrastructure access)  
4. Normalization of indicators  
5. Weighted scoring model  
6. Time series analysis  

## Project Structure

- `data/raw`: Original datasets  
- `data/staging`: Cleaned and standardized data  
- `data/prep`: Spatially filtered data (Barmbek-Süd)  
- `data/mart`: Final datasets and walkability score  
- `notebooks`: Analysis and exploration  
- `src`: Scripts for data processing and modeling  
- `outputs`: Visualizations and results  

## Data Pipeline

The project follows a structured data pipeline:

raw → staging → prep → mart

- raw: Original datasets  
- staging: Cleaned and standardized data  
- prep: Spatially filtered data (Barmbek-Süd)  
- mart: Final datasets and walkability score  

## Special Focus

- Accessibility for visually impaired individuals (e.g. street design, navigation constraints)  
- Street network structure and connectivity  

## Tools and Technologies

- Python (pandas, geopandas, numpy, matplotlib, seaborn)  
- Jupyter Notebooks  
- Git and GitHub  

## Expected Outcome

A transparent and reproducible walkability index, including insights into how infrastructure, accessibility, and modern urban services influence urban walkability.

## Author

Nicole Brüggmann
