# eqhaz-exercise
Seismic hazard exercises for the Multi Hazard course.
This repository contains tutorials for the modeling multihazard and risk course, focusing on seismic hazard assessment.

You will find Jupyter notebooks demonstrating the basic fundamentals of seismic hazard assessment.

## Getting Started

The easiest way to run the tutorials is to use Colab:
| Tutorial                                         |  |
|--------------------------------------------------|---|
| Ring of Fire                          | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FadelI/eqhaz-exercise/blob/main/00_ring_of_fire.ipynb) |
| PGV from data                         | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FadelI/eqhaz-exercise/blob/main/02_pgv_data.ipynb) |
| Magnitude-frequency relation          | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FadelI/cophil-eq/blob/main/tutorials/tut02_okada.ipynb) |
| PGA calculation from GMPE             | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FadelI/cophil-eq/blob/main/tutorials/tut02_okada.ipynb) |
| Hazard Maps                           | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FadelI/cophil-eq/blob/main/tutorials/tut02_okada.ipynb) |

## Run the Tutorials Locally

To run these tutorials locally, install Anaconda or Miniconda and create a new environment:<br>
Run the following commands in your terminal:<br>

`conda create -n seishz python==3.12 geopandas obspy folium osmnx numpy pandas matplotlib shapely cartopy os re requests zipfile`

Activate the environment:<br>

`conda activate seishz`

You can then start running the Jupyter notebooks.
