# Tesla's Sale Proportion of Electric Vehicles
## Overview
This project analyzes Tesla's proportion of electric vehicle sales in Washington state from 2012 onward. The study investigates whether Tesla's sales are higher than if consumers chose cars at random from all available electric vehicle manufacturers.

## Data Source
The dataset used in this project comes from the Washington State Electric Vehicle Population Data. It includes information about electric vehicle registrations, filtered to focus on pure electric cars sold from 2012 onward.

## Methodology
### Filtering Data: 
Removed hybrid vehicles and manufacturers producing fewer than 50 vehicles per year to ensure data quality.
### Expected vs. Actual Sales Proportions:
Calculated the expected proportion of Tesla sales assuming random manufacturer selection.
Compared this with Tesla's actual sales proportions.
### Statistical Analysis:
Used a binomial distribution to model Tesla's expected sales each year.
Computed confidence intervals to assess whether Tesla's actual sales proportions significantly deviated from random selection.
Performed hypothesis testing for 2013, as its sales proportion was closest to the expected random proportion.
## Key Findings
  - Tesla's sales proportion has consistently been higher than expected since 2014, suggesting that consumers actively choose Tesla over other brands.
  - In 2012, Tesla’s sales were lower than expected, possibly due to Nissan's dominance and Tesla's new market entry.
  - The hypothesis test for 2013 indicated that Tesla sales were slightly above random selection, though the difference was marginal.
  - The increasing number of electric vehicle manufacturers over time should, in theory, lower Tesla’s proportion, but Tesla has maintained strong market dominance.
## Limitations
Data is limited to Washington state, which may not fully represent national or global trends.
The study does not analyze potential reasons for Tesla's market share, such as pricing, production capacity, or brand perception.
## Future Work
Investigating factors influencing Tesla's dominance, such as dealership availability, pricing, advertising, and production capabilities.
Analyzing sales proportions of individual Tesla models over time to identify trends in consumer preferences.
## Authors
This project was conducted as part of a class project for STAT240 - Data Science Modeling I (001) SP23 .

