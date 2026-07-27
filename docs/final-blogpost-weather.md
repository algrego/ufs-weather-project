# A Storm's Appoaching: Creating your own Weather Forecast

A lot of people use our nation's operational weather forecasts every day, but few know how it actually works. This research shows that the complex processes inherent in understanding the weather don't need to be scary or inaccessible! With just a computer, a simple understanding of Python coding, and access to Github -- you too can be well on your way to understanding one of our nation's most important public services!

  ![Weather Briefing](../docs/Photos-for-Blog/weatherbrief.png)
  *Weather briefing in 1965 (DI02082). (1965). In NCAR/UCAR Image and Multimedia Gallery. University Corporation for Atmospheric Research (UCAR). https://n2t.org/ark:/85065/d73t9fc2 (Original work published 1965)*

## Introduction
The National Oceanic and Atmospheric Administration (NOAA) and the National Weather Service (NWS) use complex numerical models to predict the weather. This work requires access to high-performance computers (HPCs), a strong understanding of Fortran, Python, Linux, Terminal/Shell scripting, and more! Also, to fully understand how the weather models operate, scientists need a meteorlogical background to know the complex atmospheric physics equations behind the model and how to read the forecast data that is output. This makes understanding our nation's weather forecasts out of reach for most people.

But did you know the code used to create our nation's weather forecasts is publicly available? One just needs to know how to access it! 

This small notebook will demonstrate how easy it is to access forecast data and get interesting visuals and data sets to look at.

## Area of Focus
This notebook focuses on the wind from a storm that occurred on August 10th, 2020 near Cedar Rapids, Iowa. However, it is important to note that once this data is downloaded, you could look at any location in the U.S. at any time period. There are also other data that could be analyzed such as temperature, dewpoint, accumulated precipitation, snow cover, and more!

## Research Findings
Our nation has so much weather data available, right under our noses! We just have to know how to access it. This notebook shows you that you can access high quality weather data without using an expensive computer or spending hours coding in a language you don't understand. Below is an example of data that can be accessed without a supercomputer. This notebook was able to run the forecast and analysis of the wind speeds that occurred during the peak time of this storm.

  ![Derecho plotted data](../outputs/cedar_rapids_wind_timeseries.png)

This is important because the data used for our nation's forecasts is constantly being improved, and it's publicly available -- so you can improve how these models run too! This is also significant for raising awareness about available open-source coding. Students interested in learning more about all of the NOAA weather models that are available can use this notebook as a jumping off point. Students will be able to learn better when they can connect hands on experience with coding to a real lived weather experience.

  ![Derecho wind field](https://github.com/algrego/ufs-weather-project/blob/main/outputs/derecho_wind_animation.gif)

The plot above shows a visualization of an analysis run of the HRRR. This is the kind of output students could create on their own. Of any storm in the US that they find to be interesting.

 

All of the material related to this project can be found at *[https://github.com/algrego/ufs-weather-project/](https://github.com/algrego/ufs-weather-project/)*

## Implications and Future Work
This project currently pulls from archived weather forecast models. This is great for students to understand how the forecast models work and how our weather is predicted. It is not as useful if students want to actually make changes and improvements to a national model. Ideally, in the future users would be able to run their own model and modify it directly in their python notebook. Notebooks like this should be created and shared more widely across myriad ages of students to improve awareness about our nation's weather forecast capabilities and advancing weather technologies.


## Acknowledgements

Data collected https://registry.opendata.aws/noaa-hrrr-pds/ with special help from [Herbie: Download Weather Forecast Model Data in Python](https://herbie.readthedocs.io/en/stable/index.html#herbie-download-weather-forecast-model-data-in-python)
- NOAA EPIC, for the SRW tutorial, pre-staged sdata, and HPC allocation on Hercules/Orion
- Dr. Lily Jones, GEOG 5663 CApstone Instructor
- [Tutorial](https://www.ufs.epic.noaa.gov/srw-tutorial-august102020-derecho/) Rowin Smith, UFS SRW - August 10, 2020 Derecho
- Gallus, W. A., and M. A. Harrold, 2023: Challenges in Numerical Weather Prediction of the 10 August 2020 Midwestern Derecho: Examples from the FV3-LAM