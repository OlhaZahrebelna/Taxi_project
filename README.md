# Taxi Service Analysis in New York City

## Overview

This project provides an analysis of taxi service usage and costs across four boroughs of New York City: Bronx, Brooklyn, Manhattan, and Queens. The analysis is presented through a series of histograms that visualize the distribution of various metrics.

## Key Findings

### 1. Distribution of Payments and Rides

- **Bronx**: 
  - The histogram indicates that most values are concentrated at the lower end of the scale, with a gradual decline as values increase. 
  - This suggests that in the Bronx, the majority of rides or payments are relatively low compared to other boroughs.

- **Brooklyn**: 
  - Similar to the Bronx, Brooklyn shows a concentration of lower values, though with a wider spread. 
  - This indicates a diversity in travel distances or payment amounts, with many low rides but also some higher ones.

- **Manhattan**: 
  - Unlike the other boroughs, Manhattan has a distribution that peaks at higher values, indicating that rides tend to be more expensive or cover longer distances. 
  - This aligns with the higher demand and density typical of the area.

- **Queens**: 
  - The distribution shows a more balanced spread across mid-to-high values, peaking around the middle. 
  - This suggests moderate ride payments or distances, with occasional higher values.

### 2. Daily Total Rides Distribution

- **Bronx and Brooklyn**: 
  - Both boroughs show a concentration of lower daily totals, indicating a lower demand for taxi services or shorter distances for typical rides.

- **Queens**: 
  - Queens has a moderate spread, with daily totals mostly falling between 400 and 800, suggesting a slightly higher frequency of rides than Bronx and Brooklyn, but still lower than Manhattan.

- **Manhattan**: 
  - With a much higher daily total range peaking around 2500-3500, Manhattan stands out due to its role as a central business and tourist hub, resulting in significantly higher demand and longer trips.

### 3. Tips and Passenger Analysis

- A straight line from the points indicates that customers have not left tips for journeys ranging from 0 to 27 km. 
- There are cases of longer distances without tips, but no clear correlation between distance and the number of passengers is observed.
- Many outliers exist, especially for trips with one or two passengers, but the median for these groups appears the same.
- Trips with more than four passengers and cases with zero passengers (likely deliveries) are noted.

### Conclusion

The analysis highlights clear differences in taxi usage across NYC boroughs, with Manhattan having the highest daily totals and payments, while Bronx and Brooklyn show lower levels of service demand. Further exploration is needed to differentiate between groups with 0-3 passengers and those with 4-6 passengers to assess the potential benefits of increasing vehicles with larger passenger capacity.

## Requirements

- Python
- Pandas
- Matplotlib
- Seaborn
