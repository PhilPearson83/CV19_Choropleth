# Guide to creating a Covid-19 Choropleth using Folium

The map utilises open source data avaialable from the UK Government or ONS. The map focues on the South West of England but can be adapted for the whole of the UK.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PhilPearson83/CV19_Choropleth/main?filepath=CV19_Choropleth.ipynb)
<a href="https://github.com/PhilPearson83/CV19_Choropleth/blob/master/LICENSE"><img alt="License: MIT" src="https://img.shields.io/github/license/PhilPearson83/CV19_Choropleth"></a>
<a href="https://github.com/PhilPearson83/CV19_Choropleth"><img alt="PyPI" src="https://img.shields.io/badge/python-3.7+-blue.svg"></a>

[GOV.UK Coronavirus (COVID-19) in the UK](https://coronavirus.data.gov.uk/about-data)

[ONS Open Geography Portal](https://geoportal.statistics.gov.uk/)

![us](./example/positive_cases_wk_42.png)

---

_Contents:_ **[Directory Layout](#Directory-Layout)** | **[Installation](#installation)** | **[🚀 Quick Start](#-quick-start)** | **[Reference](#reference)** | **[FAQ](#faq)**

---

### Directory Layout

```
.
├── data
│   ├── geospatial
│   │   ├── DSFRS_Service_Area.cpg
│   │   ├── DSFRS_Service_Area.dbf
│   │   ├── DSFRS_Service_Area.prj
│   │   ├── DSFRS_Service_Area.qpj
│   │   ├── DSFRS_Service_Area.shp
│   │   ├── DSFRS_Service_Area.shx
│   │   ├── MSOAs.cpg
│   │   ├── MSOAs.dbf
│   │   ├── MSOAs.prj
│   │   ├── MSOAs.shp
│   │   ├── MSOAs.shx
│   └── images
│   │    ├── SampleMap.gif
├── example
│   ├── positive_cases_wk_42.png
│   └── SampleMap.gif
├── └── dsfrs_stations.csv
├── .gitignore
├── CV19_Choropleth.ipynb
├── CV19_Choropleth_with_gif_output.ipynb
├── CV19_Choropleth_with_gif_output_alt.ipynb
├── Licence
├── README.md
└── requirements.txt
```
### Installation
First clone the repository and navigate to the project's root directory:
```bash
git clone https://github.com/PhilPearson83/CV19_Choropleth.git
# navigate to the downloaded (or git cloned) material
cd ./CV19_Choropleth/
# creating a virtual environment called "env"
python -m venv env
# activating the environment
source env/Scripts/activate
```
This project is written in [`Python`](https://www.python.org/) and depends on a number packages to be installed. You can install these packages by running the following command in the project's root directory:

```bash
pip install requirements.txt 
```

### 🚀 Quick Start

## Step 1 : Start Jupyter Notebook

## Step 2 : Execute Code 

Open `CV19_Choropleth_with_gif_output.ipynb` file and rull all cells.

## Step 3 : Browse the created gif

The gif can be found at `./images/`

### Reference

### FAQ
