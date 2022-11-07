# Hawaii Climate Analysis: one-way ticket to Oahu
UC Berkeley BootCamp challenge 9 (sqlalchemy)


## Overview of the statistical analysis

To settle in Hawaii I came up with a business idea: Surf and Shake shop serving surfboards and ice cream to locals and tourists. I consider W. Avy a real investor backing to get my project off the ground. Our first meeting with him went extremely well, but he has one concern, what about the weather and asked me to assess risks based on data analysis.

## Results

### Methodology
W. Avy has stored the weather data in a SQLite database. My first step was getting acquainted with the data leveraging DB Browser SQLite. Afterwards I opened Jypiter notebook and imported SQLAlchemy Dependencies in order to complete the analysis using python programming language.
As our potential investor's primary concern is seasonality, I picked to months: June and December for comparison analysis. Then, I retrieved the tempreture and precipitation data for this periods and done simple, one-dimensional. Findings I stumbled upon are displayed beneath.

### Findings
From the summary output for two months on can conclude the following:
1. In average the tempreture in June is higher than in December by 5°F. 
2. Tempreture fluctuations are slightly higher in Desember with an std of 3.75°F
3. June is a drier month than December, yet, according to our data not significantly.

[June temperature summary](https://github.com/ArmineKhanan/hawaii_climate_analysis/blob/main/images/June%20temp.png ) 
[December temperature summary](https://github.com/ArmineKhanan/hawaii_climate_analysis/blob/main/images/December%20temp.png)
[June precipitation summary](https://github.com/ArmineKhanan/hawaii_climate_analysis/blob/main/images/June%20prcp.png)
[December precipitation summary](https://github.com/ArmineKhanan/hawaii_climate_analysis/blob/main/images/December%20prcp.png)

## Summary
To make conclusions based on our data, let's asume that th pleasant temperatures in Hawaii falls in the range from 73°F to 86°F. This would mean that June will be an absolutle favorable month for our business. It could also be assumed that December will bring some kind of profit as well taking into account that 75% of December odservations show temperature above 74°F. 
Appart from the challenge tasks we also ran code to exract comparison of precipitation data for the observed months. The rusults are presented below.
<img src="https://github.com/ArmineKhanan/hawaii_climate_analysis/blob/main/images/June%20prcp.png" width ="300"> <img src="https://github.com/ArmineKhanan/hawaii_climate_analysis/blob/main/images/December%20prcp.png" width="300" />
