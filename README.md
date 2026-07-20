# Walkability_Barmbek_Sued_Hamburg

## Walkability Analysis of Barmbek-Süd (Hamburg)

## Project Overview

This capstone project develops a transparent and reproducible walkability assessment framework for the district of Barmbek-Süd (Hamburg, Germany). The framework combines geospatial, demographic, socio-economic, infrastructure, environmental, and mobility data to evaluate pedestrian-friendly urban environments while documenting all scoring decisions in a reproducible lookup model.

## Objectives

- Build a data-driven walkability score  
- Analyze changes from 2013 to 2024  
- Investigate relationships between infrastructure and mobility behavior  
- Evaluate the role of new urban services in walkability
- Develop a transparent material-based surface evaluation model
- Build a reproducible ETL pipeline for spatial walkability analysis

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

### Surface Quality
- Walking comfort
- Accessibility
- Ecological surface quality

## Data Sources

- Hamburg district statistics (2013–2024)  
- Hamburg Geoportal (infrastructure and spatial data)  
- OpenStreetMap (points of interest, street network)  
- Mobility services (MOIA, switch points)  
- Delivery services (REWE)  
- Additional infrastructure data (e.g. schools, healthcare)  
- Hamburg Masterportal-API
- Hamburg land value data (BORIS Hamburg)

## Methodology

1. Data collection and cleaning
2. ETL pipeline (RAW → STAGING → PREP → MART)
3. Spatial filtering and feature engineering
4. Material-based surface evaluation
5. Indicator normalization
6. Weighted walkability model
7. Time series analysis

Material-specific surface types are evaluated using a transparent lookup table containing scores, documented justifications, and source references for walking comfort, accessibility, and ecological quality.

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

A transparent and reproducible walkability assessment framework, including a documented material evaluation model, spatial indicators, and reproducible ETL pipeline.

## Author

Nicole Brüggmann
