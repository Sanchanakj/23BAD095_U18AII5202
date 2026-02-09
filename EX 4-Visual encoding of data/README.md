# Experiment 4 – Visual Encoding of Traffic Accident Data

## Overview
This experiment demonstrates the application of effective visual encoding principles to traffic accident data. Using the R programming language, a scatter plot is created to visually represent accident severity, accident type, and number of casualties through color, shape, and size respectively.

## Experiment Details
- Experiment No: 4
- Title: Visual Encoding of Data
- Language: R
- Dataset: 4.traffic_accidents.csv

## Objective
To apply perceptually effective visual encoding techniques for meaningful and efficient communication of traffic accident data.

## Scenario
A city traffic department analyzes accident records to identify high-risk locations and accident patterns. Visual encoding enables quick interpretation of accident severity, frequency, and types across various locations.

## Tools & Libraries
- ggplot2 – For creating data visualizations
- dplyr – For data manipulation and preprocessing

## In-Lab Tasks
- Encode accident severity using color:
  - Minor → Green
  - Major → Orange
  - Fatal → Red
- Represent number of casualties using point size
- Represent accident type using shapes:
  - Circle → Collision
  - Triangle → Overturn
  - Square → Skid
- Plot accident data by:
  - X-axis: Location (City Road, Highway, Junction)
  - Y-axis: Vehicles Involved

## Visual Output
The scatter plot produced displays the following visual encodings:
- X-axis: Accident Location
- Y-axis: Vehicles Involved
- Color: Accident Severity
- Size: Number of Casualties
- Shape: Type of Accident
- Clear legends indicating color, size, and shape mappings

![Traffic Accident Visual Encoding](Output/Visual Encoding of Traffic Accident Data.png)

## Key Observations
- Fatal accidents are immediately distinguishable using red color
- Larger points clearly indicate high-casualty incidents
- Different shapes allow accident types to be identified without relying solely on color
- High-risk locations such as highways and junctions are easily recognizable

## Files Included
- 4.traffic_accidents.csv – Traffic accident dataset
- Exp4_VisualEncoding.R – R script for visual encoding and plotting
- Output/Visual Encoding of Traffic Accident Data.png – Scatter plot output

## Conclusion
This experiment demonstrates how visual encoding techniques such as color, size, and shape can effectively communicate complex traffic accident data. The visualization enables quick identification of accident severity, frequency, types, and high-risk locations, supporting data-driven traffic safety decisions.

## Author
Student Roll No: 23BAD095

## Date
20-01-2026
