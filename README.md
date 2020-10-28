# Guide to creating a Covid-19 Choropleth

The map utilises open source data avaialable from the UK Government or ONS. The map focues on the South West of England but can be adapted for the whole of the UK.

[GOV.UK Coronavirus (COVID-19) in the UK](https://coronavirus.data.gov.uk/about-data)

[ONS Open Geography Portal](https://geoportal.statistics.gov.uk/)

![us](./example/img/positive_cases_wk_42.png)

# Pre-requisites


# Directory Layout

```
.
├── README.md
├── .gitignore
├── Licence
├── requirements.txt
├── CV19_Choropleth_with_gif_output.ipynb
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
│   └── dsfrs_stations.csv
```

# Running the sample

## Step 1 : Start Python

``` bash
$ git clone 
$ cd /root-dir-of-the-repository
$ docker-compose up
```
On the console output copy the jupyter notebook url e.g. `http://localhost:8888/token?=xxxx` and paste in your browser.

## Step 2 : Execute Code 

Open `CV19_Choropleth_with_gif_output.ipynb` file and rull all cells.

## Step 3 : Browse the created gif

The gif can be found at `./images/`
