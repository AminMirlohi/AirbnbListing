# Exploratory Data Analysis on Airbnb Listings in New York City

## Introduction

This project is focused on performing an exploratory data analysis (EDA) of Airbnb listings in New York City. The main objective is to explore and analyze the factors that influence the listing prices, providing valuable insights for both hosts and guests. Using the Airbnb dataset for New York City, we examine the impact of various parameters, such as property type, location (neighborhood), number of reviews, availability, and customer reviews on the listing price.

Through this analysis, we are able to identify trends, relationships, and dependencies between these parameters and the pricing of Airbnb listings in NYC. The results can be used by hosts to set competitive prices based on property type, location, and other factors, while simultaneously helping guests to find the best-suited Airbnb options that fit their preferences and requirements.

## Dataset

The dataset used for this analysis is sourced from Inside Airbnb (http://insideairbnb.com), which provides publicly available information about Airbnb listings. The dataset for New York City, dated June 2021, contains the following details:

- Listing ID
- Listing name
- Host ID
- Host name
- Neighbourhood group
- Neighbourhood
- Latitude
- Longitude
- Room type
- Price
- Minimum nights
- Number of reviews
- Last review date
- Reviews per month
- Calculated host listings count
- Availability 365 (number of days the listing is available per year)

## Requirements

To execute this project, you will need the following Python libraries:

- pandas
- numpy
- seaborn
- matplotlib

## Usage

To perform the exploratory data analysis on the Airbnb listings, follow these steps:

1. Download the dataset from http://data.insideairbnb.com/united-states/ny/new-york-city/2021-06-02/visualisations/listings.csv (provided by Inside Airbnb).

2. Modify the dataset URL in `Step 2: Loading the dataset` if necessary.

3. Run the Python code provided in each step sequentially. 

4. Observe and analyze the visualizations generated to understand the factors influencing Airbnb listing prices in New York City.

## Results

The analysis provides insights into the factors that may influence the price of listings, such as property type, location, number of reviews, availability, and customer reviews. Through this exploratory data analysis, we are able to identify the impact of these factors on the listing price, which can be used by Airbnb hosts to optimize their pricing strategies.

Some key findings from this analysis include:

- The property types (Entire home/apt, Private room, Shared room) have a significant impact on listing prices, with Entire home/apt being the most expensive on average.
- Location also plays a major role in determining the price, as certain neighborhoods have higher average prices than others.
- There is a negative relationship between the number of reviews and the price, indicating that listings with fewer reviews tend to have a higher price.
- Availability seems to have an inverse relationship with price, reflecting that listings with higher prices are less likely to be available for a longer duration.
- Customer reviews per month show a scattered relationship with the price, indicating that they might not be a significant factor in determining the listing price.

With these insights and visualizations, hosts can set competitive prices based on property type, location, and other factors. At the same time, guests can use this information to find affordable and suitable Airbnb options that fit their preferences and requirements.
