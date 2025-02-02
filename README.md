# DTSA-5301

## Overview
This repository contains two data analysis projects exploring COVID-19 trends in Costa Rica and NYC shooting patterns. Both projects leverage R for data cleaning, visualization, and statistical modeling.

## Projects
### Costa Rica COVID-19 Analysis

File: covid19_analysis.Rmd

Objective: Track the progression of COVID-19 cases and deaths in Costa Rica.

**Key Features:**

* Data transformation from raw JHU CSSE time-series

* Visualization of monthly trends (cases/deaths)

* Quadratic regression modeling to identify wave patterns

* Peak mortality identification (May/Sep 2021)

### NYC Shooting Analysis

File: shooting_project.Rmd

Objective: Investigate demographic and spatial patterns in NYC shootings (2022-2023).

**Key Features:**

* Geolocation mapping of female victim shootings

* Temporal analysis of perpetrator-victim sex combinations

* Linear modeling of shooting trends over time

* Identification of male-dominated violence patterns

## Installation

```r
install.packages(c("tidyverse", "lubridate", "janitor"))
```

## Data Sources

### COVID-19 Data

Johns Hopkins University CSSE:

https://github.com/CSSEGISandData/COVID-19

### NYC Shooting Data

NYC OpenData:

https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8
