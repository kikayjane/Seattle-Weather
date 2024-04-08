# Weather Repository
The purpose of this project is to convince Dr. Egan's parents to visit him in Seattle by investigating whether it rains more in NYC or Seattle.

## Data
The datasets are from NOAA National Centers for Environmental Information that includes records of daily percipitation from Seattle and New York City for the 3 year period January 2020 - January 2024.
It can be found here: https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND

## Data Preparation
To prepare the data for visualization, the following steps were taken:
  1. Describe the source of the data
  2. Inspect the contents of each data set
  4. Convert the columns to the correct data types
  5. Remove unnecessary parts
  6. Identify missing values and impute the NaN values
  7. Join the Seattle and New York data frames
  8. Ensure the data frame is in a tidy format
  9. Rename columns and values

The file "data_preparation.ipynb" contains the coding that performs the data preparation, and the results can be found in the "clean_seattle_nyc_weather.csv" file, both linked in the repository.
