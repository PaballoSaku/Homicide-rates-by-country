# Homicide-rates-by-country

![](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)

<div id="main image" align="center">
  <img src="[https://github.com/PaballoSaku/Homicide-rates-by-country/blob/main/crime_scene.jpg]" width="450" height="300" alt=""/>
</div>

### Table of Content

* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)


## 1. Project Overview <a class="anchor" id="project-description"></a>

This project analyses homicide rates across various 
- countries
- regions, 
- and subregions

It aims to identify trends, disparities, and patterns in global violence. 

Using Exploratory Data Analysis (EDA), statistical summaries, and visualisations, we explore the distribution of homicides over time, highlighting key hotspots and regions with the highest and lowest homicide rates.

By the end of this project,  we are going to have a clear understanding of global homicide trends, identifying which countries and regions experience the highest and lowest homicide rates. We are going to analyse how homicide rates have changed over time and compare different continents and subregions to understand geographical disparities.

Through data visualisations such as bar charts, treemaps, and graphs, we are going to gain insights into patterns and trends in homicide data.

## 2. Dataset <a class="anchor" id="dataset"></a>

- **Total Entries:** 195 rows
- **Columns:** 6

**Column Descriptions**

- **Location:** The name of the country or territory.
- **Region:** The continent or broader geographical grouping.
- **Subregion:** A more specific geographical region within the continent.
- **Rate:** The homicide rate per 100,000 people.
- **Count:** The total number of homicides in that country for the specified year.
- **Year:** The year for which the homicide data is recorded.

## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:

+ `Pandas` and `Numpy`
+ `Matplotlib`
+ `Plotly`
+ `Seaborn`

## 4. Environment <a class="anchor" id="environment"></a>

It's highly recommended to use a virtual environment for your projects, there are many ways to do this; we've outlined one such method below.

### Create the new evironment - you only need to do this once

```bash
# create the conda environment
conda create --name <env>
```

### This is how you activate the virtual environment in a terminal and install the project dependencies

```bash
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt
```
