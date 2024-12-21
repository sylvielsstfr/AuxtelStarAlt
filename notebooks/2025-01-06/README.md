# README.md

- Author Sylvie Dagoret-Campagne
- Creation : August 23th 2023
- update : December 21th 2024

Series of tools to prepare Auxtel observations.
The novelties is building the list of target from the getCalspec tool

## Dependencies


### Date and time

pip install datetime
pip install timezonefinder

- note calendar is included in python distribution


### IPYALADIN

pip install ipyaladin
pip install sidecar
pip install regions
pip install MOC

### NOIRLAB data access 
pip install --ignore-installed --no-cache-dir astro-datalab

## Must use notebook:
- **01_ObservationOfVisibleCalspecList.ipynb** 

## Backup notebook:
- **BuildVisibleCalspecList.ipynb**

## Old notebooks:
- use it if getCalspec not working


- sky trajectories : **plot_obs-planning-cerropachon_fewtargets-wthmag-12Sept2023.ipynb**

                         
- polar plot : **plot_obs-planning-cerropachon_fewtargets-polarplot.ipynb**


## Example of polar plot :
- example :   plot_polar_ext.ipynb
