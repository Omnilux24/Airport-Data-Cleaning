# Airport Data Cleaning Case Study

## Introduction

This repository contains a case study on cleaning and sorting airport data from a CSV file. The goal of this project is to provide a clean dataset for further analysis or visualization. The data includes information about airports, such as IATA codes, names, locations, and more.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Cleaning](#data-cleaning)
- [Data Sorting](#data-sorting)
- [Data Visualization](#data-visualization)
- [File Output](#file-output)
- [How to Use](#how-to-use)
- [Dependencies](#dependencies)
- [License](#license)

## Project Overview

### Data Source

The dataset used in this case study is sourced from a CSV file, which contains information about various airports.

### Objectives

1. Clean the data by removing unnecessary characters and fixing formatting issues.
2. Sort the data based on multiple columns to make it more organized.
3. Visualize the geographical distribution of airports using latitude and longitude.
4. Output the cleaned and sorted data to a new CSV or Excel file.

## Data Cleaning

In this step, we cleaned the data by addressing the following issues:

- Removed unnecessary commas from the 'AIRPORT' column.
- Addressed any formatting inconsistencies.

## Data Sorting

To ensure data consistency and organization, we sorted the dataset by the following columns:

- IATA_CODE
- AIRPORT
- CITY
- STATE
- COUNTRY
- LATITUDE
- LONGITUDE

## Data Visualization

We visualized the geographical distribution of airports using a scatter plot. This visualization helps provide insights into the locations of airports.

![Airport Locations](images/airport_locations.png)

## File Output

The cleaned and sorted data is saved to a new CSV file named `cleaned_sorted_airports.csv`. You can also find the data in an Excel file named `cleaned_sorted_airports.xlsx`.

## How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/omnilux24/airport-data-cleaning.git
