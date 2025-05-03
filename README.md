### MSc Geographic Information Systems EGM722_Project / Ulster University

# Mapping Lepidoptera Biodiversity Hotspots in Northern Ireland (2014 - 2024) using Python and NBN Atlas Data

## Description
This project demonstrates how to map biodiversity hotspots for butterflies and moths in Northern Ireland using open data from the National Biodiversity Network (NBN) Atlas. The aim of the study is to visualise areas with high species richness and assess biodiversity patterns, helping inform conservation and land management efforts.  
The project uses Python to process, clean and analyse lepidoptera occurrence data, and to create species richness maps. The maps will be overlain with protected areas for enhanced ecological insights. 

## Contents
- Setup and Installation
  - Getting Started
  - Optional Steps
  - Download/Clone the Project Repository
  - Setting up the Conda Environment
  - Additional Setup Steps
- How to use Project
- Credits
- License


## Setup and Installation
### Getting Started
To get started on the project, `git` and `conda` must be installed on your computer. The `git` installer for your operating system can be downloaded from [GitHub](https://git-scm.com/downloads).

To install `conda`, the graphical interface Anaconda Navigator can be downloaded from [https://www.anaconda.com/download/success](https://www.anaconda.com/download/success). 

### Optional Steps
It is recommended to open a GitHub account to enable working through the project and to create a fork of the repository. A free account is available at [https://github.com/](https://github.com/).  

### Download/Clone the Project Repository
**The project repository is available at:** [https://github.com/izlbyzl/egm722_project_02](https://github.com/izlbyzl/egm722_project_02)    

Fork the repository to your GitHub account, then clone your fork.  

### Setting up the Conda Environment
After cloning the repository, create a `conda` environment using the **environment.yml** file provided in the repository. 

Using Anaconda Navigator, select **Import** from the **Environments** panel.  
Or  
From the directory where the project is cloned, run command prompt or terminal with the following command:  

`conda env create -f environment.yml`  

The dependencies this project requires are:
- `numpy`: for performing mathematical functions [https://numpy.org/](https://numpy.org/)
- `geopandas`: for working with geospatial data [https://geopandas.org/en/stable/](https://geopandas.org/en/stable/)
- `matplotlib`: for visualising data [https://matplotlib.org/](https://matplotlib.org/)
- `cartopy`: for producing maps and geospatial data analysis [https://scitools.org.uk/cartopy/docs/latest/](https://scitools.org.uk/cartopy/docs/latest/)
- `jupyter-lab`: interactive script notebook [https://jupyter.org/](https://jupyter.org/)
- `pandas`: for data analysis and manipulation [https://pandas.pydata.org/](https://pandas.pydata.org/)
- `shapely`: for manipulation and analysis of polygons [https://pypi.org/project/shapely/](https://pypi.org/project/shapely/)
- `ipywidgets`: adds interactive widgets to Jupyter [https://ipywidgets.readthedocs.io/en/stable/](https://ipywidgets.readthedocs.io/en/stable/)
- `pyepsg`: provides access to EPSG codes [https://pyepsg.readthedocs.io/en/latest/](https://pyepsg.readthedocs.io/en/latest/)
- `seaborn`: provides statistical data visualisation [https://seaborn.pydata.org/](https://seaborn.pydata.org/)

Finally launch `jupyter-lab` from your `conda` environment and work through the code. 

### Additional Setup Steps
Northern Ireland shapefile (**.shp**) containing vector data covering, counties, towns, lakes, Areas of Outstanding Natural Beauty (AONB's) and Areas of Special Scientific Interest (ASSI's) was collected and prepared for use by Ulster University, in the Geographic Information Systems (GIS) MSc. Sourced from: [Ordnance Survey of Northern Ireland (n.d.).](https://www.nidirect.gov.uk/articles/osni-open-data-product-list)  

Species occurrence data was downloaded from the [National Biodiversity Network (NBN) Atlas (2025).](https://nbnatlas.org/) A search for the order *Lepidoptera* gives access to a UK dataset. Records were refined using search parameters to include data from a specific location (NI), time-frame (2014 -2024) and other filter parameters (verification: accepted and human observation). The final selection was then downloaded in **.csv** format. Once downloaded, unnecessary columns were removed from the dataframe, ensuring species names, geographic coordinates (latitude/longitude) and date columns remained. 

### Credits
Robert McNabb' GitHub: [https://iamdonovan.github.io/teaching/egm722/index.html](https://iamdonovan.github.io/teaching/egm722/index.html)   
NBN Atlas Team and contributing Citizen Scientists

### License
This project is licensed under the GNU General Public License v3.0, see LICENSE file for details.
