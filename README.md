# Understanding Our Nation's Forecast System: A Storm in Cedar Rapids, Iowa

## The Unified Forecast System (UFS) is a community-based, coupled, comprehensive Earth modeling system. The [Short Range Weather Application](https://github.com/ufs-community/ufs-srweather-app/) (SRW-APP) is a development branch that targets predictions of atmospheric behavior on a limited spatial domain and on time scales from minutes to several days.

Our nation relies on earth system models that are computationally massive, solving fluid dynamic equations across millions of grid points for hours. These efforts require access to NOAA's Research and Developement High Performance Computing System (RDHPCS), which are difficult to access and expensive to run. This project develops a **pre-executed python notebook** that can be used as a learning tool for understanding how our forecast models work even when access to high performance computers (HPCs) are not available.

This project will utilize the [Short Range Weather App Tutorial: Sumulating the August 10 2020 Derecho](https://ufs.epic.noaa.gov/srw-tutorial-august102020-derecho/) to create a clean and runnable workflow for understanding and visualizing this modeling platform and related output. Ideally, this framework could be utilized to represent any Application being run by the UFS and can be updated in the future to apply to other relevant numerical weather prediction processes.  

# What data does it use, and where does the data come from?

# How do I set up the environment to run the code?


# How is the repo organized?

## Environments

# Citations and Acknowledgements
- **NOAA EPIC** for the SRW tutorial, pre-staged data, and HPC allocation on Hercules/Orion
- **Dr. Lilly Jones**, GEOG 5663 Capstone Instructor
- **Rowin Smith**, UFS Student Ambassador, [Short Range Weather App Tutorial: Simulating the August 10 2020 Derecho](https://www.ufs.epic.noaa.gov/srw-tutorial-august102020-derecho/)

# Background on the UFS Short-Range Weather Application
The Unified Forecast System (UFS) is a community-based, coupled, comprehensive Earth modeling system. NOAA's operational model suite for numerical weather prediction (NWP) is quickly transitioning to the UFS from a number of legacy modeling systems. The UFS enables research, development, and contribution opportunities within the broader Weather Enterprise (including government, industry, and academia). For more information about the UFS, visit the UFS Portal at https://ufs.epic.noaa.gov/.

The UFS includes multiple applications (see a complete list at https://ufs.epic.noaa.gov/applications/) that support different forecast durations and spatial domains. This documentation describes the development branch of the UFS Short-Range Weather (SRW) Application, which targets predictions of atmospheric behavior on a limited spatial domain and on time scales from minutes to several days. The development branch of the application is continually evolving as the system undergoes open development. The latest SRW App release (v3.0.0) represents a snapshot of this continuously evolving system. 

The UFS SRW App User's Guide associated with the development branch is at: https://ufs-srweather-app.readthedocs.io/en/develop/, while the guide specific to the SRW App v3.0.0 release can be found at: https://ufs-srweather-app.readthedocs.io/en/release-public-v3.0.0/. The repository is at: https://github.com/ufs-community/ufs-srweather-app.

For instructions on how to clone the repository, build the code, and run the workflow, see:
- https://ufs-srweather-app.readthedocs.io/en/release-public-v3.0.0/UsersGuide/BuildingRunningTesting/Quickstart.html

For a debugging guide for users and developers in the field of Earth System Modeling, please see:
https://epic.noaa.gov/wp-content/uploads/2022/12/Debugging-Guide.pdf

UFS Development Team. (2025, Apr. 9). Unified Forecast System (UFS) Short-Range Weather (SRW) Application (Version v3.0.0). Zenodo. https://doi.org/10.5281/zenodo.14834682

[![Python unittests](https://github.com/ufs-community/ufs-srweather-app/actions/workflows/python_unittests.yaml/badge.svg)](https://github.com/ufs-community/ufs-srweather-app/actions/workflows/python_unittests.yaml)
[![Python functional tests](https://github.com/ufs-community/ufs-srweather-app/actions/workflows/python_func_tests.yaml/badge.svg)](https://github.com/ufs-community/ufs-srweather-app/actions/workflows/python_func_tests.yaml)
