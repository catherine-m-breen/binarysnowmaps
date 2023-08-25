# Binary Snow Maps Jupyter Book

[![Deploy](https://github.com/geo-smart/use_case_template/actions/workflows/deploy.yaml/badge.svg)](https://github.com/geo-smart/use_case_template/actions/workflows/deploy.yaml)
[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](https://geo-smart.github.io/use_case_template)
[![GeoSMART Use Case](./book/img/use_case_badge.svg)](https://geo-smart.github.io/usecases)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/geo-smart/use_case_template/HEAD?urlpath=lab)
[![Open in Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/geo-smart/use_case_template)


This tutorial provides instructions for how to use camera trap images to convert satellite snow maps to binary snow maps for hydrologic forecasting and wildlife modelling. We will show you how to extract or classify snow from camera trap images. Then, using the cameras as on-the-ground information, we will show you how to conduct an analysis to identify the best threshold in the satellite data that "cuts" or separates the satellite data into "snow" and "no snow" pixels. We conduct this analysis using images from 1181 wildlife cameras deployed by the Norwegian Institute for Nature Research (NINA), but we show how one could repeat this analysis using publically available from wildlifeinsights.org, a database of over 1,374 camera traps studies from around the world. As an outcome of this tutorial, we hope that you can repeat these steps to create a custom binary snow map using camera traps from your region of interest. 

The overall workflow of this tutorial is summarized below, with the target map the black & white binary snow map: 


## Prerequisites

In this tutorial we assume you have some knowledge of the following: 
- Python programming
- Data manipulation with pandas
- Threshold analyses, including a receiver-operating curve analyses


## Scientific abstract:

Snow covers a maximum of 47 million km2 of Earth's northern hemisphere each winter and is an important component of the planet's energy balance, hydrology cycles, and ecosystems. Monitoring regional and global snow cover has increased in urgency in recent years due to warming temperatures and declines in snow cover extent. Optical satellite instruments provide large-scale observations of snow cover, but cloud cover and dense forest canopy can reduce accuracy in mapping snow cover. Remote camera networks deployed for wildlife monitoring operate below cloud cover and in forests, representing a virtually untapped source of snow cover observations to supplement satellite observations. Using images from 1181 wildlife cameras deployed by the Norwegian Institute for Nature Research (NINA), we derived a threshold to create daily binary maps of snow cover from the MOD10A1 product. The threshold corresponding to snow presence was an NDSI value of 40.50, which closely matched a previously defined global binary threshold of 40 using the MOD10A2 8-day product. This model demonstrates the utility of camera trap networks for validation of snow cover products from satellite remote sensing.



![logo](https://github.com/catherine-m-breen/binarysnowmaps/blob/main/book/img/funders.png)

