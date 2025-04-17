# egm722_project
 Final project for EGM722. How-to Guide and GitHub Repository.
# Mapping Lepidoptera Biodiversity Hotspots in Northern Ireland using Python and NBN Atlas Data

## Description
This project demonstrates how to map biodiversity hotspots for butterflies and moths in Northern Ireland using open data from the National Biodiversity Network (NBN) Atlas. The aim of the study is to visualise areas with high species richness and assess biodiversity patterns, helping inform conservation and land management efforts.  
The project uses Python to process, clean and analyse the butterfly occurrence data, and to create species richness maps. The maps will be overlain with protected areas for enhanced ecological insights. 

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
To get started on the project, <mark style='color: pink'>git</mark> and <mark>conda</mark> must be installed on your computer. The <mark>git</mark> installer for your operating system can be downloaded from [GitHub](https://git-scm.com/downloads).
To install <mark>conda</mark>, the graphical interface Anaconda Navigator can be downloaded from [Anaconda](https://www.anaconda.com/download/success). 

### Optional Steps
It is recommended to open a GitHub account to enable working through the project and to create a fork of the repository. A free account is available at [GitHub](https://github.com/).  

It is also recommended to use an integrated development environment (IDE) such as PyCharm or VSCode to write your code. Downloads are available from:
- **PyCharm Community Edition** [jetbrains](https://www.jetbrains.com/pycharm/download/)
- **VSCode** [Visual Studio Code](https://visualstudio.microsoft.com/downloads/)

### Download/Clone the Project Repository
The project repository is available at: 
[https://github.com/izlbyzl/egm722_project_02](https://github.com/izlbyzl/egm722_project_02)    
First, fork the repository to your GitHub account, then clone your fork using the following command:  
'''git clone https://github.com/{your username}/egm722_project_02'''  
replacing <mark>{your_username}</mark> with your GitHub username.

If you do not have a GitHub account, the project repository can be cloned using:  
'''git clone https://github.com/izlbyzl/egm722_project_02'''

### Setting up the Conda Environment
After cloning the repository, a conda environment is created using the environment.yml file provided in the repository. 

Using Anaconda Navigator, select **Import** from the **Environments** panel.  
Or  
From the directory where the project is cloned, run command prompt or terminal with the following command:  
'''conda env create -f environment.yml'''  

### Additional Setup Steps

## How to use Project


### Credits
Bob's iamdonovan github\
NBN Atlas Team

### License
This project is licensed under the GNU General Public License v3.0, see LICENSE file for details.
