# Predicting Scooter utilization

Using data provided by the city of Austin, TX, this project predicts the demand in various census tract neighborhood throughout the city.

## File Descriptions

**Capstone 1 Final Report.pdf — Start here!** This report describes the process of gathering the data and creating the machine learning analyses.  The report includes links to the appropriate notebook for each section

census_2010_tracts_core.pdf — This is a map of the census tracts used in the project.

data_wrangling.ipynb — This Jupyter notebook contains the code used wrangle and clean the data

data_story.ipynb — This Jupyter notebook contains the code used to create initial visualizations and understand the data.

statistical_data_analysis.ipynb — This Jupyter notebook contains the code used to analyze the data and perform Bayesian MCMC analysis.

machine_learning_analysis.ipynb — This Jupyter notebook contains the final machine learning techniques used to predict the results described in the report

ct data — folder that includes centroid and GIS data for the data_story

## Getting Started

1.  To run these Jupyter notebooks on your machine, clone the entire file set to your repository.
2.  Download the csv from https://data.austintexas.gov/Transportation-and-Mobility/Shared-Micromobility-Vehicle-Trips/7d8e-dm7r
(The data is updated daily, so depending on your download date, you will have a larger data set than me.)
3.  Place the csv in the working directory.
4.  Open and run the desired Jupyter notebook  Note that some notebooks will run other notebooks using magics, so all must be downloaded together.

## Prerequisites

The Python 3 environment uses the following modules:
To install these in an Anaconda environment, use these commands:
-Pandas
-Matplotlib
-Seaborn
-Geopandas
-Shapely
-Sci-kit Learn
-datetime
-time
-tabulate
-Facebook Prophet

## Author

* **Trevor Bhattacharya** - trev.bhatt@gmail.com

## Public opinion
https://xkcd.com/2188/
