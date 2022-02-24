# Visualize LA 311 data 

Need a simple verion of results from [access the data workshop](https://github.com/researchsherpa/access-the-data-workshop-311-analysis) for the Graffiti Removal request type.

I built this to be compact so it could run in binder.

## Contents

- Data directory contains two files: 1) geojson for 2021 graffiti removal requests; and 2) a clean version of Neighborhood Council polygons.

- Notebooks directory contains single notebook with multiple visualizations of the requests

- Notebook can be explored with binder [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/researchsherpa/graffiti-viz/main?urlpath=lab)


## Setting Up Local Env

I use jupyter lab with ipywidgets and folium. The recipe is:

  1. Assuming anaconda is installed, repo cloned, and you're in the directory environment.yml can be used to build a baseline lab env with conda:  `conda env create -f environment.yml`
  
  2. Activate the new env: `conda activate graffiti-viz`
 
  3. Fire up lab via `jupyter lab`
  
  4. Explore

foo
