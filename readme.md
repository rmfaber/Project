# Project Introduction
The goal of this project is to show relations between COVID-19 incidence / fatality rates and some background characteristics on a municipal level within the Netherlands.

The project consists of three main parts:
1. Collecting and combining the data 
2. Visualizing the relationships
3. Modelling the relationships

Each part is carried out in a separate jupyter notebook. 

## Installation?

* Requirements.txt?
* What do people need to run the program?
* Dump the environment?

# 1. Collecting and combining the data

The associated jupyter notebook is Prepare_data.ipynb.

This notebook automatically collects data from RIVM and CBS sources through their api's and combines the two datasets. The notebook also collects geological data and maps from PDOK to visualize the data.

All data is publicly accessible and does not relate to individual people.

Data is stored locally so that it can be retrieved easily afterwards. Data storage is not updated in git.

# 2. Visualizing the relationships

The aim is to visualize relationships between COVID-19 incidence / fatalities and a few interesting characteristics of a municipality, such as the socio-demographic composition (more elderly, more religious, etc.) and relevant behavioural characteristics (mobility, adherence to lock-down measures, vaccination status, etc.)

# 3. Modelling the relationships

Finally I strive to model the relationships between some of the aforementioned characteristics.

First I think I would use a simple multi-linear regression of some sort, with cumulative incidence / fatality as the dependent variable.

This analysis can be expanded upon with a time-series analysis.
