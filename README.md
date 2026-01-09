[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18201502.svg)](https://doi.org/10.5281/zenodo.18201502)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Pseudo dynamic scripts for HLMA
This repository contains the analysis scripts and documentation used to derive storm-scale electrical organization diagnostics from the Houston Lightning Mapping Array (HLMA) data.

## Authors
- Timothy Logan
- Krishna Calindi

## Data requirements
The scripts use data form the following sources:
- Storm specific Lightning Mapping Array (LMA) data obtained using the lasso selection method in the `XLMA` software.
- Flash initiation files obtained by analyzing the exported file from XLMA with `lmatools` software.
- SPC storm report data obtained from the NOAA (National Oceanic and Atmospheric Administration) website
- Radar reflectivity and radial velocity files obtained from `NEXRAD`
- TVS and MESO event data obtained from Iowa Environmental Mesonet of Iowa State University
- Shapefie of US counties obtained from the US Census Bureau
