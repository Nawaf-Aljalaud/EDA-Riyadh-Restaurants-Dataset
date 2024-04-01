# EDA-Riyadh-Restaurants-Dataset
Data Analysis Module Exploratory Data Analysis 

This repository contains an analysis of a dataset of restaurants. Each row in the dataset represents a restaurant, and the columns provide various details about each restaurant.

## Dataset Description

The dataset includes the following columns:

- `name`: The name of the restaurant. Some names are only available in Arabic.
- `categories`: A list of categories (in English) separated by a comma.
- `address`: The address according to Foursquare. Unfortunately, it is the least useful column in the dataset because lots of restaurants lack a formal address. The future version of this dataset may include an enhanced address format.
- `lat`: Latitude.
- `lng`: Longitude.
- `price`: Shows the price category (Cheap, Moderate, Expensive, Very Expensive).
- `likes`: The number of likes.
- `photos`: The number of photos. Photos themselves are not included.
- `tips`: The number of tips in Foursquare (e.g., Don't miss their pasta). Tips themselves are not included.
- `rating`: The average rating out of 10.
- `ratingSignals`: The number of raters.

## Insights from Restaurant Dataset Analysis

1. **Imports and Dataset Loading**: The notebook starts by importing necessary libraries and loading a restaurant dataset. It explores the structure of the dataset, including the number of entries and the data types of each column.

2. **Handling Missing Values and Duplicates**: The notebook checks for missing values and duplicates in the dataset. Rows with missing values and duplicates are dropped to ensure data integrity for further analysis.

3. **Univariate and Bivariate Analysis**: The notebook performs univariate analysis to understand the distribution of individual variables. It also performs bivariate analysis to explore relationships between variables. For instance, it creates a bar plot to show the relationship between the price of the restaurants and the number of likes they have received.

4. **Feature Engineering**: The notebook creates new features that might be useful for analysis, such as combining latitude and longitude into a single 'location' feature.

5. **Encoding Categorical Variables**: The notebook encodes categorical variables, such as the 'price' category, into numerical values. This is a common preprocessing step in machine learning applications.

6. **Insights from the Analysis**: The insights gained from this analysis could be used to understand patterns and trends in the restaurant industry. For example, understanding the relationship between price and popularity could help a restaurant owner decide how to price their dishes to attract more customers. Similarly, understanding the geographical distribution of restaurants could help identify areas with high or low competition. The encoded price feature could be used in a machine learning model to predict a restaurant's popularity based on its price category.

## Resources

The data used in this analysis was obtained from the following sources:

- The restaurant dataset was downloaded from Kaggle: [Riyadh Restaurants Dataset](https://www.kaggle.com/datasets/fahd09/riyadh-restaurants-20k/data)

- Additional data was scrapped from [(foursquare.com)](https://foursquare.com/)

Please note that the data is subject to the terms and conditions of the respective sources.

