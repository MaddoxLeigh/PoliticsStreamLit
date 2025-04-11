
# UK Crime Statistics Analysis

This project provides tools and analysis for working with UK crime statistics and other government data. It includes data processing scripts and visualizations to help understand crime patterns and trends across different regions of the UK.

## Project Overview

The project contains:
- Crime rate data for various UK regions (London, Newcastle, etc.)
- Data processing and analysis scripts
- Visualization tools for crime statistics
- Integration with the UK Government's API for accessing official statistics

## Data Sources

The project uses data from:
- UK Government API (api.beta.ons.gov.uk)
- Local crime statistics datasets
- Historical crime rate data

## Getting Started

1. Clone this repository
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook `apiukpresentation.ipynb` to explore the data and analysis

## Data Files

- `crimerates_most_popular.csv`: Comprehensive crime rate data
- `crime_rates_2022_newcastle.csv`: Newcastle-specific crime data for 2022
- `crimecategorylondon2022.csv`: Crime categories in London for 2022
- `crimerates2021.csv`: Historical crime rate data from 2021
- `crime_rates_2022_london.csv`: London-specific crime data for 2022

## Features

- Data processing and cleaning
- Statistical analysis
- Data visualization
- API integration with UK government data sources
- Regional crime rate comparisons

## Usage

The main analysis can be found in the `apiukpresentation.ipynb` Jupyter notebook, which demonstrates:
- How to access UK government data through their API
- Data processing and analysis techniques
- Visualization of crime statistics
- Regional comparisons and trends

## Project Structure

```
.
├── docs/                  # Documentation
├── site/                  # Generated site content
├── crimerates_most_popular.csv
├── crime_rates_2022_newcastle.csv
├── crimecategorylondon2022.csv
├── crimerates2021.csv
├── crime_rates_2022_london.csv
└── apiukpresentation.ipynb
```
