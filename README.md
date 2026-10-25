# coastal-chlorophyll-enso-iod-sst-bangladesh
Python code and Jupyter Notebooks for analyzing coastal chlorophyll-a variability and its relationship with ENSO, IOD, and SST
# Chlorophyll-a variability and its relationship with ENSO, IOD and Sea Surface Temperature in the coastal water of Bangladesh

This repository contains the modular Python code and Jupyter Notebooks used for data processing, statistical diagnostics, and analysis presented in the manuscript submitted to *Regional Studies in Marine Science*.

## 📁 Repository Structure & Workflow
├── 01_SST_CHL_NC_Data_QC.ipynb                # Quality control, metadata audits, missing data checks, and valid pixel thresholding on raw NetCDF datasets
├── 02_Data_extraction_&_preprocess.ipynb      # Spatial masking, time-series extraction, anomaly calculations, detrending, standardization and multi-source dataset alignment
├── 03_Study_area_Fig_generation.ipynb         # High-resolution spatial map generation detailing study area boundaries, bathymetry, and region of interest
├── 04_Timeseries_Figure_Generation.ipynb      # Production of publication-quality anomaly time-series
├── 05_Lagged_analysis_of_Climate_CHL.ipynb    # Cross-correlation analysis and lead-lag impact evaluation between climate drivers and coastal parameters
├── 06_Bivariate_correlation_&_MLR_with_ARMA.ipynb # Bivariate correlation, Multiple Linear Regression (MLR), state-space modeling, and ARMA error adjustments
└── README.md                                  # Repository documentation
## 📦 Required Python Libraries
To run or inspect the notebooks, the following standard scientific Python packages are required:
- `numpy`
- `pandas`
- `xarray`
- `matplotlib`
- `statsmodels`
- `scipy`
- `cartopy`
- 'openpyxl'

## 📊 Data Availability
- Input data filenames match the variables specified within the notebooks. 
- Original satellite datasets (Copernicus, Modis-Aqua) and climate indices (BOM) are publicly available from their respective official repositories as cited in the manuscript.
