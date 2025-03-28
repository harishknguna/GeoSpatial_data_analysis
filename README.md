# GeoSpatial Data Analysis for Weather Prediction

## Context

A client in Australia owning forestry plantations is looking to be covered against wildfires and excess of rain. Both perils can damage forests. The test is centered on these 2 perils which are ones of the perils we are specialized at Descartes Underwriting. Wildfires are characterized by two phases: the ignition and the propagation. Here, we will mainly focus on the ignition part. The ignition point is where the wildfire starts and can be caused by natural (lightning for example) or human factors (cigarette, campfire, powerlines,...).

Historical ignition points provide us with knowledge on what influences ignition and can help us for better simulating widlfires.

## Structure of the repo

There a 3 jupyter notebooks in this repo. The 1st and 3rd notebooks are centered on wildfires while the 2nd one is on excess of rain.

- The wildfire part will be tackled in the 1st and 3rd notebooks. The steps are the following:
  - Get information about historical ignition points (temperature of the day, type of vegetation) in the 1st notebook preceded by a tuto on `xarray` package
  - Finally, we need to design a classification algorithm that looks at historical ignition points to compute an ignition probability and this will be done in the 3rd notebook
- The part on excess of rain will be tackled in the 2nd notebook where you will be asked to compute the historical payouts of a client and use geospatial data

### Description of the notebooks

- The first notebook is a tutorial on the package `xarray` used for manipulating geospatial data. In the end of the notebook, you will be asked to find information about historical ignition points.

- In the 2nd notebook, you will be asked to manipulate `xarrays`, understand the notion of resolution, manipulate timeseries and compute historical payouts for an excess of rain cover.

- The 3rd notebook is the core of the technical test and is a classification problem. Below is a more detailed description.

These 3 notebooks are an illustration of part of the content of the job at Descartes Underwriting as an Underwriter or R&D Data Scientist that consists mostly of a mix between Physics, Data Manipulation, Statistics and Machine Learning.


## Data

The aim of the 3rd notebook is to write a functional and structured code in `python` using a `jupyter` notebook.

The code should be able to make a prediction on the dataset of ignition/non-ignition points leading to wildfires and constructed by Descartes Underwriting's team

The data can be found in this repository

The target for this project is `ignition`
