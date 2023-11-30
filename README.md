# Uber Data Analysis

## Overview

This repository contains code and visualizations for analyzing Uber trip data. The analysis focuses on various aspects such as revenue growth, traffic patterns, popular pickup and drop-off locations, and insights into trip distances and durations. The analysis is conducted using Python and visualized with Matplotlib and Seaborn.

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## Data

The dataset used for this analysis is Uber trip data, which includes information such as trip distance, duration, pick-up and drop-off locations, and more.

## Analysis Steps

### 1. Month Over Month Base Revenue Growth

Calculate and visualize the month-over-month percentage growth in Uber's base revenue. Annotate the total cumulative growth for the period.

### 2. Worst Traffic Day of the Week

Determine and visualize which day of the week experiences the worst (slowest) traffic overall. This analysis includes creating a bar plot to compare median trip speeds on different weekdays.

### 3. Median Distance Traveled per Trip

Explore the median distance traveled per trip and identify patterns, especially focusing on the differences around 5 AM. Hypothesize reasons for longer distances at this time, considering potential connections to public transportation.

### 4. Popular Pickup and Drop-off Taxi Zones

Identify the most popular pickup and drop-off taxi zones and visualize their distribution. Additionally, explore the percentage of trips represented by the top five origins/destinations.

### 5. Pickup and Drop-off Location Pairs

Create a heatmap visualizing the total number of trips for each pickup and drop-off location pair.

### 6. Mean Time and Distance from Popular Pickup Location

Analyze the mean travel time and distance from the most popular pickup location (zone 2A) to various destinations. Visualize the results through bar plots.

### 7. Variable Distributions and Bivariate Relationships

Explore the distributions of trip distance, duration, and average speed. Investigate the relationship between trip distance and duration and identify outliers.

### 8. Weekday Average Speed

Examine the median trip average speed during weekdays and visualize the peak hours during rush traffic.

### 9. Peak Hour Classification

Create a new variable indicating whether a trip occurred during peak hours (7-9 AM and 4-6 PM) and visualize the total number of trips per month during peak and off-peak hours.

## Conclusion

This analysis provides valuable insights into Uber's revenue growth, traffic patterns, and user behavior. The visualizations help to understand the dynamics of the Uber dataset and make data-driven decisions.
