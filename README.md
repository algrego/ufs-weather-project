# Project Title
Understanding Our Nation's Forecast System: A Storm in Cedar Rapids, Iowa

# Project Description
The Unified Forecast System (UFS) is a community-based, coupled, comprehensive Earth modeling system. The [Short Range Weather Application][https://github.com/ufs-community/ufs-srweather-app/] (SRW-APP) is a development branch that targets predictions of atmospheric behavior on a limited spatial domain and on time scales from minutes to several days.

Our nation relies on earth system models that are computationally massive, solving fluid dynamic equations across millions of grid points for hours. These efforts require access to NOAA's Research and Developement High Performance Computing System (RDHPCS), which are difficult to access and expensive to run. This project develops a **pre-executed python notebook** that can be used as a learning tool for understanding how our forecast models work even when access to high performance computers (HPCs) are not available.

This project will utilize the [Short Range Weather App Tutorial: Sumulating the August 10 2020 Derecho][https://ufs.epic.noaa.gov/srw-tutorial-august102020-derecho/] to create a clean and runnable workflow for understanding and visualizing this modeling platform and related output. Ideally, this framework could be utilized to represent any Application being run by the UFS and can be updated in the future to apply to other relevant numerical weather prediction processes.  



# What data does it use, and where does the data come from?

# How do I set up the environment to run the code?

# How is the repo organized?

## Environments
- `environment-srw.yml` — for running the UFS SRW App
- `environment-notebook.yml` — for Jupyter notebook analysis (cfgrib, xarray, cartopy, matplotlib)
# Who made it, and is there a citation or acknowledgement?