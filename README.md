# Flood Risk Map — KwaZulu-Natal (April 2022 Floods)

An interactive web map built for *DRR1141 (Introduction to Hazards and Disasters)*, first semester, University of Venda.

🔗 *Live map:* https://munzheleleuhone77-design.github.io/flood-risk-map/

## Overview

This project visualises flood risk exposure across localities in the eThekwini/KwaZulu-Natal region, using the *April 2022 KwaZulu-Natal floods* as the primary case study. It maps a composite flood risk score for key affected areas (uMlazi, Inanda, KwaMashu, Chatsworth, Ntuzuma, Pinetown, Durban CBD, Tongaat, Verulam, and Umzinto), alongside major river/drainage lines.

## Methodology

The composite risk score for each locality is intended to combine five factors:

1. *Rainfall intensity* — storm/precipitation data for the event period
2. *River / drainage proximity* — distance to major rivers and stormwater channels
3. *Slope and elevation* — terrain steepness and low-lying exposure
4. *Land use / imperviousness* — built-up vs. vegetated surface cover
5. *Settlement density* — population and informal settlement exposure

> *Note:* The risk scores currently shown are illustrative placeholders based on documented impact of the 2022 floods, standing in for a full GIS overlay analysis. They are intended to be replaced with values computed from real spatial datasets (see below).

## Tools & Data

- *QGIS* — spatial analysis and layer preparation
- *Python* — geopandas, rasterio for the geoprocessing pipeline
- *Folium / Leaflet* — interactive web map rendering
- *Hosting* — GitHub Pages

## Status

- [x] Interactive map with composite risk layer, river layer, legend, and basemap toggle
- [ ] Replace illustrative risk scores with real GIS-derived values (rainfall, DEM, river network, land use datasets)
- [ ] Add data sources and citations once real datasets are integrated

## Author

Created by Munzhelele Uhone, Department of Geography and Environmental Sciences, University of Venda.
