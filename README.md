# gun-violence

This project was completed for the final project of MAP 674, Spatial Data Analysis and Visualization, as part of the New Maps Plus program.

## Project Goals
The goal of this project is to use pandas and GeoPandas to explore and clean a dataset within a Jupyter notebook, ultimately resulting in a clean dataset that can be pulled into a webmap. Find the notebook and initial data in the 'notebooks' directory.

The resultant webmap shows violent gun incidents aggregated by congressional district, with a popup linking to the webpage of each district's representative where you can explore their stance on gun control or contact them about the issues. Find the mapped data and index.html file in the 'map' directory.

## How to run the notebook
Clone this repository to run the notebook. You will need to install pandas, GeoPandas, and Matplotlib. Once installed, all data used in the notebook is either read from an external source or is included in this repository and referred to by relative paths.

#### Data Sources
The CSV file obtained for this project was retrieved from [Gun Violence Data](https://github.com/jamesqo/gun-violence-data), an accessible database compiled through webscraping of [Gun Violence Archive](https://www.gunviolencearchive.org/). Gun Violence Archive is a non-profit research organization that documents gun incidents and crimes.

additional data used: [Congressional District Shapefile](https://opendata.arcgis.com/datasets/ff48bbae433442a38f6c635b8c7baf72_0.zip), [congress-legislators](https://github.com/unitedstates/congress-legislators)
