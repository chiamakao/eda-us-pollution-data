# Exploratory Data Analysis on U.S Pollution Data

check out the jupyter notebook here: https://jovian.ai/olivelikes2chat/eda-on-us-pollution-data

## Introduction
Air pollution is one of the outstanding environmental concerns in the world today, affecting both developed and developing regions. In 2016 alone, it accounted for 4.2 million deaths globally and over 59,000 in the U.S, because of it's association with stroke, lung canncer, ischemic heart disease, acute lower respiratory disease and chronic obstructive pulmonary disease. Although there has been a significant downward trend in the number of deaths from 1990 to 2016 in the U.S, which could be as a result of stricter regulations, it is still imperative that we monitor these pollutants, by using measures such as air quality index, which translates numerical data into a descriptive rating scale and makes it easier for citizens of all ages to understand the level of pollution in the air they breathe.

## Project Objective & Outline
In this project, we will perform exploratory data analysis (EDA) on a dataset documented by the U.S. EPA on pollution caused by four major pollutants. This dataset has a total of 28 fields. The four pollutants ( NO2, SO2, CO, and O3) each have 5 specific columns. Observations totaled to over 1.7 million.

Why EDA?

Exploratory Data Analysis (EDA) refers to the process of performing initial investigations on data so as to discover patterns, spot anomalies, test hypothesis and check assumptions with the help of summary statistics and graphical representations. EDA helps to understand the data first and try to gather as many insights from it as possible.

For our analysis, we will be specifically looking at air quality index(AQI) of these pollutants in some key states and be making comparisons of their yearly, monthly and daily concentrations.

Source: The data used for this analysis was scrapped from the database of U.S. EPA: Link

Here's an outline of the steps we will follow:

* Download the dataset from kaggle using the opendatasets library
* Preprocess the data and clean using the pandas library
* Perform exploratory analysis and visualization using some python visualization libraries such as matplotlib, seaborn, plotly and folium
* Ask and answer relevant questions using the data to gain deep understanding and make useful inferences
