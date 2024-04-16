# Weather Repository

## Description
The purpose of this project is to convince Dr. Egan's parents to visit him in Seattle by investigating whether it rains more in NYC or Seattle. The goal is to inform travel plans based on the likelihood of encountering rain. Utilizing NOAA's environmental data, we analyzed daily precipitation records from January 2020 to January 2024.

The methodology encompassed data cleaning, categorization of rainfall intensity, and statistical analysis to compare average monthly precipitation, the frequency of rain levels (light to no rain, moderate, heavy), and total annual precipitation across both cities.

Our analysis revealed that SEA generally experiences a higher frequency of rainy days, particularly moderate to heavy rain during fall and winter. Contrary to expectations, NYC accumulated a greater total annual precipitation, suggesting heavier downpours occur despite fewer rainy days. These findings suggest that while SEA has more consistent rain, NYC's precipitation is more variable, with instances of intense rainfall contributing to its higher annual totals.

## Requirements
*  Colab

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

## Analysis
To create the visualizations for analysis, the following steps were taken:
  1. Load the clean data and review its contents
  2. State specific questions about the data that can be answered with the visualizations
  3. Perform various analyses utilizing different types of graphs
  4. Finalize the chosen visualizations to produce conclusions

The file "seattle_nyc_analysis.ipynb" contains the coding that performs the visualization analysis, also linked in the repository.

## Authors
Rica Bayani-Dahilig (me)

## License
