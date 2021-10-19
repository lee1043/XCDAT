# XCDAT Validation and Tutorials

This repository explores the the capabilities of [xarray](https://github.com/pydata/xarray) and [XCDAT](https://github.com/XCDAT/xcdat) for climate data analysis. It comprises of tutorials and validation of a subset of [CDAT](https://github.com/CDAT/cdat) functions in xarray/XCDAT using Jupyter Notebooks.

## Getting Started

### Setup

1. Clone this repo

   ```bash
   git clone https://github.com/XCDAT/xcdat_test
   ```

2. Create and activate the XCDAT Anaconda test environment

   ```bash
   cd xcdat_test
   conda env create -f conda-env/test.yml
   conda activate xcdat_test
   ```

3. Start working with the Jupyter Notebooks!

### Demo input preparation

[PMP download data for prepare demos](https://github.com/PCMDI/pcmdi_metrics/blob/master/doc/jupyter/Demo/Demo_0_download_data.ipynb)

```bash
wget https://raw.githubusercontent.com/PCMDI/pcmdi_metrics/master/doc/jupyter/Demo/Demo_0_download_data.ipynb
```

## Contents

- Temporal average

  - [Seasonal average](compare_cdat_xarray/seasonal_averages.ipynb)
  - [Annual cycle](compare_cdat_xarray/annual_cycle.ipynb)
  - [Annual cycle departure](compare_cdat_xarray/annual_cycle_departure.ipynb)
  - [Annual cycle climatology](compare_cdat_xarray/annual_cycle_climatology.ipynb)

- Spatial average

  - [Explore spatial averages](compare_cdat_xarray/explore_spatial_averages.ipynb)

- Regrid
  - [Regrid example](compare_cdat_xarray/Regrid_ex1.ipynb)

## FYI: Useful External Resources

- [Xarray Docs](https://xarray.pydata.org/en/stable/index.html)
- [XCDAT Docs](https://xcdat.readthedocs.com)
- Xarray usage examples

  - [A Quick Introduction to CMIP6](https://towardsdatascience.com/a-quick-introduction-to-cmip6-e017127a49d3)
  - [Creating a subset of dataset using Xarray](https://www.nccs.nasa.gov/nccs-users/instructional/adapt-instructional/python/xarray-monthly-climatology)
  - [Xarray Access CMIP5 Data (NCI data training)](https://nci-data-training.readthedocs.io/en/latest/_notebook/climate/1_01_Xarray_access_CMIP5.html)
  - [Visualize Climate data with Python](https://nordicesmhub.github.io/climate-data-tutorial/03-visualization-python/)

- Visualization examples

  - [Hawkins Warming Stripes](https://towardsdatascience.com/climate-heatmaps-made-easy-6ec5be0be6ff)
  - [Map using proplot](https://towardsdatascience.com/a-quick-introduction-to-cmip6-e017127a49d3)
  - [Map using cartopy](https://nordicesmhub.github.io/climate-data-tutorial/03-visualization-python/)
