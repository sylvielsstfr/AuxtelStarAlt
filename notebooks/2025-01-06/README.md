# README.md

- Author Sylvie Dagoret-Campagne
- Creation : August 23th 2023
- update : December 21th 2024

Series of tools to prepare Auxtel observations.
Access to sky tracks and spectra to help for target selection

- CALSPEC and GAIA


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

Note that ipyaladin requires widgets. It is recommended to install
ipyaladin according instructions given here:

- https://github.com/cds-astro/ipyaladin?tab=readme-ov-file#installation

      git clone https://github.com/cds-astro/ipyaladin.git
      cd ipyaladin
      npm install
      npm run dev

(unnecessary installation of widgets 
conda install -c conda-forge ipywidgets)

https://ipywidgets.readthedocs.io/en/7.x/user_install.html

### getCalspec

### getGaia


### NOIRLAB data access 
    pip install --ignore-installed --no-cache-dir astro-datalab

## Must use notebook:
- **01a_ObservationOfVisibleCalspecList.ipynb**
- **01b_ObservationOfVisibleCalspecList.ipynb**  : save as above but reorganised
- **01c_ObservationOfVisibleGaiawdList.ipynb**  : save as above but reorganised

## Backup notebook:
- **BuildVisibleCalspecList.ipynb**

## Old notebooks:
- use it if getCalspec not working


- sky trajectories : **plot_obs-planning-cerropachon_fewtargets-wthmag-12Sept2023.ipynb**

                         
- polar plot : **plot_obs-planning-cerropachon_fewtargets-polarplot.ipynb**


## Example of polar plot :
- example :   plot_polar_ext.ipynb
