# Adaptive-Frontline-Governance-Sustains-Rural-Infrastructure-Projects – Code Repository

Codes to reproduce the results of the paper **“Adaptive Frontline Governance Sustains Rural Infrastructure Projects During Economic Crisis.”**

## Overview

This repository contains the code used to run the difference-in-difference (DiD) analysis and DiD with heterogeneous effects that evaluate the impact of project completion of irrigation infrastructure rehabilitation on paddy field extent and how the expenditure rate (as a proxy for project downscale) affects this impact. The scripts are written in Python and R.

## Repository Structure

```
code/
 └  Frontline_governance.ipynb

README.md
```

## Requirements

The codes were developed using Python 3.12. Main dependencies include:

* pandas
* numpy
* statsmodels
* cycler
* matplotlib

## Data

* Esri Sentinel-2 10-Meter Land Use/Land Cover data:
https://livingatlas.arcgis.com/landcoverexplorer/

* WorldPop population data:
https://hub.worldpop.org/geodata/summary?id=25742

* Sri Lanka's rural irrigation infrastructure rehabilitation project data:
Not publicly available. Please contact the Irrigation Department of Sri Lanka.
