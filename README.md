# A Guide to creating a Covid-19 Choropleth

The map utilises open source data avaialable from the UK Government or ONS. The map focues on the South West of England but can be adapted for the whole of the UK.

[GOV.UK Coronavirus (COVID-19) in the UK](https://coronavirus.data.gov.uk/about-data)

[ONS Open Geography Portal](https://geoportal.statistics.gov.uk/)

# Pre-requisites


# Directory Layout

```
.
├── README.md
├── .gitignore
├── Licence
├── world_obesity.ipynb
├── data
│   ├── images
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
│   └── geospatial
│   │    ├── 
│   └── dsfrs_stations.csv
```

# Running the sample

## Step 1 : Starting docker container

``` bash
$ git clone 
$ cd /root-dir-of-the-repository
$ docker-compose up
```
On the console output copy the jupyter notebook url e.g. `http://localhost:8888/token?=xxxx` and paste in your browser.

## Step 2 : Execute Code 

Open `world_obesity.ipynb` file and rull all cells.

## Step 3 : Start bokeh server

In the browser using the jupyter notebook go to the `Terminal` 

```
bokeh serve --show world_obesity.ipynb
```
## Step 4 : Browse the interactive map

The interactive map is rendered by bokeh server which can be browsed at `http://localhost:5006/`
