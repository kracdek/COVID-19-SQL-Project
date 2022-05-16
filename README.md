# COVID-19 SQL Data Exploration Project

## Introduction
This covid-19 analysis was one of the detailed project I worked on using the dataset from WHO.TThe Covid-19 pandemic affected the World on a Global scale. This analysis purpose was to know the effect of pandemic in each continents, drilling down to countries to determine the extent of severity of the pandemic.

## Tools
This project uses following languages/tools
* Microsoft Excel : To understand the dataset we are dealing with.
* MySQL : For further analysis.
* Tableau Public: For further visualization

## Project 
We're looking at global Covid-19 deaths data and comparing those numbers/percentages between countries or continent, and visualizing them. This repository Data Analysis and Visualisation is performed to show trends or comparison of Covid-19 deaths data.

## Data

The data for this assignment can be viewed from the link given below:

   - [Coronavirus (COVID-19) Deaths Data](https://ourworldindata.org/covid-deaths)
   
The file contains the data frame with all the COVID-19 cases worldwide information. Here is aquick glance of the following columns I used:

### Columns

* `iso_code`	ISO 3166-1 alpha-3 – three-letter country codes
* `continent`	Continent of the geographical location
* `location`	Geographical location
* `date`	Date of observation
* `population`	Population in 2020
* `total_cases`	Total confirmed cases of COVID-19
* `new_cases`	New confirmed cases of COVID-19
* `total_deaths`	Total deaths attributed to COVID-19
* `new_deaths`	New deaths attributed to COVID-19



## Data Preparation
This step is used to process data cleaning and ensuring that the dataset is free from errors and unwanted outliers when starting the analysis.
- Explore and observe data.
- Check for and treat missing values.
- Transform data-format types.
- Deleted unwanted columns such as Hospitalized Patients, Mortality rate e.t.c
- Deleted dates after the May 2021.
  
Further analysis took place in MySQL Workbench.

Checkout my [SQL code here](https://github.com/kracdek/COVID-19-SQL-Project/blob/main/COVID-19%20Project.sql)

## Data Visualization
Result Tableau visualization is [here](https://public.tableau.com/app/profile/kris6374/viz/Book1____16474663393430/Dashboard1)

## Major Insights
- US had the Highest date confirmed cases and deaths
- US, UK, Spain, Italy, France, Germany, Turkey, Iran, China, and Switzerland had the most confirmed cases.
- US, UK, Italy, France, Spain, Belgium,  Germany, Iran, Netherlands, and China where leading top 10 in confirmed deaths.
- Saint Helena has recorded zero (0) cases
