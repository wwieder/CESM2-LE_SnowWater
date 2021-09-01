# CESM2-LE_SnowWater repositiory
Notebooks here were used to make figures in Wieder et al. 2021, submitted to Nature Climate Change
The workflow here is build around using the CESM2 large ensemble data from [Rodgers et al. 2021](https://esd.copernicus.org/preprints/esd-2021-50/) on NCAR's casper cluster


Scripts here were built around a framework develped by Daniel Kennedy, with improvements suggested by Anderson Banihirwe
I have provided a conda environment to help avoid package mismatch:

Create the environment with:

`conda env create -f environment.yml`

Then you should hopefully have **lens-py** available as an environment in JupyterHub
