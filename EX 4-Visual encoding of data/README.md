# Experiment 4 – Visual Encoding of Traffic Accident Data
 
## Overview
This experiment demonstrates effective visual encoding principles applied to traffic accident data. The R programming language is used to create a scatter plot where accident severity, type, and casualties are represented using color, shape, and size respectively.
 
## Experiment Details
- **Experiment No:** 4  
- **Title:** Visual Encoding of Data  
- **Language:** R  
- **Dataset:** `4.traffic_accidents.csv`  
 
## Objective
To apply perceptually effective visual encoding techniques for meaningful data communication in traffic accident analysis.
 
## Scenario
A city traffic department analyzes accident records to identify high-risk zones and patterns of accident severity. Visual encoding helps in quick understanding of accident frequency, severity, and types across different locations.
 
## Tools & Libraries
- **ggplot2** – For creating scatter plots  
- **dplyr** – For data manipulation  
 
## In-Lab Tasks
- Encode accident **severity** using color:
  - Minor → Green  
  - Major → Orange  
  - Fatal → Red  
- Represent accident **casualties/frequency** using point size  
- Represent accident **type** using shapes:
  - Circle → Collision  
  - Triangle → Overturn  
  - Square → Skid  
- Plot accidents by **Location** (X-axis) and **Vehicles Involved** (Y-axis)  
 
## Visual Output
The scatter plot produced displays:
- **X-axis:** Accident Location (City Road, Highway, Junction)  
- **Y-axis:** Vehicles Involved  
- **Color:** Severity of accident (Minor → Green, Major → Orange, Fatal → Red)  
- **Size:** Number of casualties (larger points = more casualties)  
- **Shape:** Type of accident (Collision, Overturn, Skid)  
- Clear legends showing mapping of color, size, and shape  
 
![Traffic Accident Visual Encoding](EX 4-Visual encoding of data/Output/Visual Encoding of Traffic Accident Data.png)
 
## Key Observations
- Fatal accidents are immediately visible using red color  
- Larger points highlight high-casualty incidents  
- Different shapes distinguish types of accidents without relying on color alone  
- The plot allows easy identification of high-risk locations (City Road, Highway, Junction)  
 
## Files Included
- `4.traffic_accidents.csv` – Traffic accident dataset  
- R script (`Exp4_VisualEncoding.R`) – Code for visual encoding and plotting  
- Screenshot of the scatter plot  
 
## Conclusion
The experiment demonstrates how visual encoding (color, size, shape) can effectively communicate complex traffic data. The scatter plot helps quickly identify accident severity, frequency, type, and high-risk locations, supporting data-driven traffic safety decisions.
 
## Author
- Student Roll No: `23BAD095`  
 
## Date
- 20.01.2026
