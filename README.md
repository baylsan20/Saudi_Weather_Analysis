# Saudi Arabia Weather Data Analysis

## Project Overview

This project analyzes weather data across Saudi Arabia using **Power BI**, with the goal of transforming raw data into an interactive dashboard and extracting meaningful **Actionable Insights**

## Data Understanding & Cleaning

I started by profiling the dataset and reviewing its structure, data types, missing values, numerical fields, categorical fields, and time-related columns

Using **Power Query**, I cleaned and transformed the data by validating data types and preparing the temperature, wind, date, year, month, day, and hour fields for analysis

## Data Modeling

I built a **Star Schema** with **FactWeather** as the central fact table and related dimensions such as **Date, City, and Time**

This structure helped organize the data and improved filtering, aggregation, and DAX calculations

## DAX Measures

Created dynamic measures including:

* **Average Temperature:** 24.72
* **Maximum Temperature:** 50
* **Minimum Temperature:** -4
* **Average Wind:** 12.96
* **Weather Records**
* **Average Humidity**

## Data Analysis & Visualization

The dashboard focuses on key analytical questions through:

* **Top 6 Cities by Average Temperature**
* **Average Temperature by Month**
* **Average Temperature by Hour**
* **Max vs Min Temperature by City**
* **Most Common Weather Conditions**

I used **Top N Filtering** to focus on the six cities with the highest average temperatures and selected suitable visualizations such as Line Charts, Clustered Column Charts, and Pie Charts based on the analytical purpose

## Key Insights

* Overall average temperature was approximately **24.72°C**
* Maximum recorded temperature was **50°C**
* Minimum recorded temperature was **-4°C**
* Average temperature peaked around **14:00**
* Temperature patterns varied across cities and months
* Clear and Sunny were among the most common weather conditions

## Interactivity

Instead of using slicers, I used **Visual Interactions / Cross-filtering**, allowing users to select a value such as **Mecca** directly from a visual and automatically update the other visuals based on the selection

## Tools

**Power BI | Power Query | DAX | Star Schema | Data Modeling | Data Visualization**
