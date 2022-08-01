# Seattle-Airbnb-Analysis

### Table of Contents
1. [Installation](#installation)
2. [Motivation](#motivation)
3. [File Description](#files)
4. [Results](#results)
5. [Licensing](#licensing)

## Installation <a name="installation"></a>
Python 3.8.12 was used on Jupyter Notebook IDE. The following packages are required and should all be installed directly with Anaconda:
- numpy 1.21.5
- pandas 1.4.1
- scikit-learn 1.0.2
- collections

## Motivation <a name="motivation"></a>
In this notebook, we analyze data for Airbnb listings in Seattle from Kaggle to look for patterns that point to what kind of listing features such as neighborhood, property type, amenities, etc. would appeal strongly to customers. Specifically, I examine four questions as follows:
- What are the most expensive neighborhoods and property types?
- What features best correlate to high ratings for listings?
- What kinds of listings get high numbers of reviews?
- What months of the year are most common for bookings in multi-bedroom listings?

## File Description <a name="files"></a>
The two datasets listings.csv and reviews.csv from [Kaggle](https://www.kaggle.com/airbnb/seattle/data) are directly attached in the repo. The first file, listings.csv, contains data on all Airbnb listings in Seattle pulled from their online pages, such as their location, review scores, number of beds and baths, etc. The other one, reviews.csv, contains data on all reviews written for all listings in Seattle from 2009 to 2016.

The code is executed in the Jupyter Notebook file Seattle_AirBnb_analysis.ipynb, which is written fully in Python 3.

## Results <a name="results"></a>
See the results discussed in this Medium post.

## Licensing <a name="licensing"></a>
As per the [original data source](http://insideairbnb.com/get-the-data/), this data is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
