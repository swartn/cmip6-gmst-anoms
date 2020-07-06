# CMIP6 GMST anomalies

Repository of notebooks for computing GMST anomalies in CMIP6, relative to the 1850 to 1900 mean, using pangeo stack and Google Cloud CMIP6 data. This is done for realization `r1i1p1f1` of all available models, and for the historical and tier 1 SSP experiments. CSV files of the result are also provided here. This work can be cited using the doi: 

[![DOI](https://zenodo.org/badge/259493437.svg)](https://zenodo.org/badge/latestdoi/259493437)

Run the notbook computation yourself online using pangeo binder:

[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/swartn/cmip6-gmst-anoms.git/master?filepath=gmst_cmip6.ipynb)

# Notebooks
- gmst_cmip6.ipynb : compute GMST anomalies for all CMIP6 models
- gmst_cmip6_parallel.ipynb : Slightly optimized version using dask clients (30-50% speedup)
- gmst_canesm5.ipynb : As for CMIP6, but using only CanESM5 large ensemble (50 members)

# CSV files
The notbook outputs CSV files for each experiment (historical, and tier 1 SSPs). CSV files list the annual mean GMST by year (row) and model (column). The following files are available in this repository:

- cmip6_historical_gmst_swartn_gmst_anoms.csv
- cmip6_ssp126_gmst_swartn_gmst_anoms.csv
- cmip6_ssp245_gmst_swartn_gmst_anoms.csv
- cmip6_ssp370_gmst_swartn_gmst_anoms.csv
- cmip6_ssp585_gmst_swartn_gmst_anoms.csv


# License
[Open Government License - Canada](https://open.canada.ca/en/open-government-licence-canada)

# Author
Neil Swart, CCCma, April 2020.

[@neil_c_swart](https://twitter.com/Neil_C_Swart)

