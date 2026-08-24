---
title: "Vermont Respiratory Pathogen Wastewater Monitoring"
date: 2026-08-18T11:26:24-04:00
---

The [Vermont Respiratory Pathogens Wastewater Monitoring dashboard](https://jacob-pancoast17.shinyapps.io/vrpwm-dashboard/) (VRPWM) is a resource meant to present weekly published CDC NWSS data in a digestible format for both researchers and casual observers.

Every week on Friday, the CDC updates NWSS monitoring datasets for Influenza A, COVID-19, and RSV. Using GitHub Actions, this data is automatically read in using an R script that runs every Saturday at 00:00 EST. The pipeline I created is executed, which follows the CDC's pipeline for calculating wastewater viral activity levels (WVALs), found [here](https://www.cdc.gov/wastewater/about/wval.html). The WVAL metric is valuable since it standardizes data across different sites by comparing current levels of virus to low levels at that site over the last 24 months.

The CDC monitors state-level wastewater data [here](https://www.cdc.gov/wastewater/respiratory-viruses/state.html), however this resource only allows you to check current WVALs. The VRPWM includes fully customizable date ranges (accounting for the requirement that a valid site needs at least 8 weeks worth of data). This allows for historical analysis of wastewater concentrations of viral respiratory pathogens.

This tool was created after considering my conclusions in my research paper published earlier this summer (see [here](https://jacob-pancoast17.github.io/rsv-epidemiology/)), which concluded wastewater surveillance is an invaluable tool to predict seasonality of respiratory pathogens, monitor clinical burden in conjunction with hospitalization data, and inform public health guidelines for immunization timelines and testing protocols.
