# Airbnb Data Analysis

This project aims to analyze the Airbnb listing data to uncover patterns, distributions, and relationships between different variables. It involves data cleaning, analysis, and data visualization to derive insights.

## Dataset

The dataset contains :

  - Listing ID and Name
  - Host details (ID, name, identity verification status)
  - Location details (neighbourhood group, neighbourhood, latitude, longitude, country)
  - Property characteristics (room type, construction year, price, service fee, minimum nights)
  - Review information (number of reviews, last review date, reviews per month, review rate)
  - Availability and house rules


## Analysis Steps

 - Distribution Plots: Count plots for neighbourhood group and room type, and histograms for numerical features like price, minimum nights, and more.
 - Import Libraries: I Imported libraries like numpy, pandas, seaborn, and matplotlib.pyplot for data manipulation and visualization.
 - Loaded the dataset.
 - Explored the dataset to understand its structure, size, data types, and missing values.
 - Data Cleaning: I dropped 4 columns, removed duplicates and changed the name of some neighbourhood variables removed 
 - performed Exploratory Data Analysis (EDA) using Various plots and statistical analyses to gain insights into the data distributions and relationships between variables.

## Visualizations

  - Distribution Plots: Count plots for neighbourhood group and room type, and histograms for numerical features like price, number of reviews, minimum nights, etc.
  - Geographical Distribution: A scatter plot showing Airbnb listings' geographical spread (latitude vs. longitude), forming recognizable NYC borough shapes.
  - Relationship Plots:
      1 Box plots to compare price across different room types and neighbourhood groups.
      2 Heatmap visualizing the correlation matrix of numerical features.
      3 Scatter plots to examine relationships such as number of reviews vs. reviews per month, and price vs. minimum nights.

