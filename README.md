# Comparison with Altimetric Data
Contains MATLAB scripts for comparing altimetric river water level data with CaMa-Flood model outputs (sfcelv: Water Surface Elevation, and rivout: Discharge) for the Niger and Ganges-Brahmaputra river basins.

The comparison is performed in two ways:

  1. The first temporal components from altimetric data and CaMa-Flood outputs are extracted and compared.
  2. Time series from selected virtual stations are compared to the closest CaMa-Flood output.

The altimetric data is accessible with the link:
https://github.com/XIVAliakbarZarkoob/Altimetric-Data-Check/tree/main/Data

MATLAB script V09 uses files from folders with the same name as the compressed data files.

MATLAB script V10 opens a window for each data source to select desired data. 

The CaMa-Flood output files required for running this script is stored of google drive accessible with the link:
https://drive.google.com/drive/folders/1gnALukgkgDRnXFPZQBUvw0sqKTq2AO-D?usp=sharing

# Runoff Regionalization
Contains MATLAB scripts for regionalizing global runoff data. The script trims global NetCDF runoff files on the Niger and Ganges-Brahmaputra basins and export the results as new NetCDF files.
