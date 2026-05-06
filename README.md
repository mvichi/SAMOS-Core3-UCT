# AOS-SAMOS Core 3 module - python in ocean sciences
Material for the python in ocean sciences module of the AOS-SAMOS course: Core 3 Quantitative skills for Ocean Sciences.
This material was prepared by M. Vichi and M. Mangatane from the Deaprtment of Oceanography, University of Cape Town

We ackowledge funding from the project 101179091 — SAMOS — ERASMUS-EDU-2024-CBHE funded by the European Union.

## Day 1
Morning
* Introduction to SCDM (30 minutes)
* Hands-on tutorial: jupyterlab (1 hour)
* The computer interface- operating systems and * filesystems (1.5 hours)

Afternoon
* Hands-on Tutorial: Programming and data (1.5 * hours)&nbsp;
* DataCamp assignment: importing data in python (2 hours)

## Day 2
Morning
* Data Management
* Hands-on Tutorial: Multidimensional Data and xarray

Afternoon
* Hands-on Tutorial (continued)
* DataCamp assignment: matplotlib

## Day 3
Morning
* Introduction to revision control systems
* Hands-on Tutorial: git and GitHub
* Assignment E2: Loading and visualizing data from flat files (using AI)

Afternoon
* Hands-on Tutorial: Mapping with Cartopy
* Assignment E3: Using cartopy for mapping

## Day 4
Morning
* Hands-on Tutorial: Extracting and visualizing data with xarray

Afternoon
* Consultations and catch-ups

## Day 5
Morning
* Hands-on Tutorial: Advanced computation with xarray
* Explanation of the group assignment (E5)

Afternoon
* Assignment E4: DMP

## Installation of the conda environment
Download the `samos-core3.yml` file in your Download folder. This file contains the packages to install in your new conda environment. 
Open the Anaconda prompt, change directory to the Download folder where the file is located; create the new environment and activate it

`conda env create --solver libmamba -f samos-core3.yml`

`conda activate samos-core3`

You can now launch `jupyter lab`, which will use the new kernel and packages.

### Special Acknowledgment
Some components of this course have been adapted from: 
https://earth-env-data-science.github.io/intro.html
and from other publicly available material on the web as indicated in the material. This material is made available under a CC-BY-SA-4.0 licence.
