# Mosquito Alert Sampling Effort Data
Open access data on Mosquito Alert participation and sampling effort.

## Description

This dataset contains data on participation and sampling effort in the [Mosquito Alert](http://www.mosquitoalert.com/) citizen science system. It can be used for a variety of purposes, including (a) to adjust estimates of mosquito population densities and human-mosquito encounters based on sampling effort, and (b) to better understand the dynamics of citizen scientists' participation. The data is organized spatially by grids of "sampling cells," drawn at intervals of 0.05 degree and 0.025 degree latitude and longitude, and it is based on optional anonymous background tracks from the Mosquito Alert app. The dataset includes raw track counts aggregated in sampling cells, along with estimates of sampling effort based on a model of participants' propensity to send any report as a function of the time elapsed since they first began participating.

## Contents

The repository contains the following files:

* `sampling_effort_daily_cellres_025.csv.gz` - Daily participation and sampling effort in 0.025 degree sampling cells.
* `sampling_effort_daily_cellres_025_metadata.json` - Metadata for the 0.025 degree sampling cell data. 
* `sampling_effort_daily_cellres_05.csv.gz` - daily participation and sampling effort in 0.05 degree sampling cells.
* `sampling_effort_daily_cellres_05_metadata.json` - Metadata for the 0.05 degree sampling cell data. 
* `CITATION.cff` - Shows how to cite this dataset.
* `LICENSE` - License for this dataset.
* `.gitignore` - Specifies which files are excluded from the git repository.
* `README.md` - This file.

## Permanent Location

All releases from this repository are also hosted on Zenodo. The latest versions can be found at:

[![DOI:10.5281/zenodo.5802476](https://zenodo.org/badge/DOI/10.5281/zenodo.5802476.svg)](
https://doi.org/10.5281/zenodo.5802476)


