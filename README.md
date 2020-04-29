# CMIP6 GMST anomalies

Repository of notebooks for computing GMST anomalies in CMIP6, relative to the 1850 to 1900 mean, using pangeo stack and Google Cloud CMIP6 data.

Run it with the pangeo binder:

[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/swartn/cmip6-gmst-anoms.git/master?filepath=gmst_cmip6.ipynb)

# Notebooks
- gmst_cmip6.ipynb : compute GMST anomalies for all CMIP6 models
- gmst_cmip6_parallel.ipynb : Slightly optimized version using dask clients (30-50% speedup)
- gmst_canesm5.ipynb : As for CMIP6, but using only CanESM5 large ensemble (50 members)

# License
Canadian Open Government License 
https://open.canada.ca/en/open-government-licence-canada

# Author
Neil Swart, CCCma, April 2020.
@neil_c_swart

