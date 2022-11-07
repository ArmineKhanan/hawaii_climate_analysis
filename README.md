# Hawaii Climate Analysis: one-way ticket to Oahu
UC Berkeley BootCamp challenge 9 (sqlalchemy)


## Overview of the statistical analysis

To settle in Hawaii, I come up with a business idea: A Surf and Shake shop serving surfboards and ice cream to locals and tourists. I consider W. Avy a potential investor backing to get my project off the ground. Our first meeting with him went well, but he has some concerns about the weather. Hence he asked me to assess risks based on data analysis.

## Results

### Methodology
W. Avy has stored the weather data in SQLite database. My first step was getting acquainted with the data leveraging DB Browser SQLite. Afterward, I opened the Jypiter notebook and imported SQLAlchemy Dependencies to complete the analysis using the python programming language.
As our potential investor's primary concern is seasonality, I picked two months: June and December for comparative analysis. Then, I retrieved the temperature and precipitation data for this period and did simple, one-dimensional. The findings I stumbled upon are displayed beneath.

### Findings
From the summary output for two months on can conclude the following:
1. On average the temperature in June is higher than in December by 5°F. 
2. Temperature fluctuations are slightly higher in December with an std of 3.75°F
3. June is a drier month than December, yet, according to our data not significantly.

[June temperature summary](https://github.com/ArmineKhanan/hawaii_climate_analysis/blob/main/images/June%20temp.png) 

[December temperature summary](https://github.com/ArmineKhanan/hawaii_climate_analysis/blob/main/images/December%20temp.png)

[June precipitation summary](https://github.com/ArmineKhanan/hawaii_climate_analysis/blob/main/images/June%20prcp.png)

[December precipitation summary](https://github.com/ArmineKhanan/hawaii_climate_analysis/blob/main/images/December%20prcp.png)

## Summary
To make conclusions based on our data, let's assume that the pleasant temperatures in Hawaii fall in the range of 73°F to 86°F. Hence, June is  a beneficial month for our business. Considering that 75% of December observations show temperatures above 74°F, December will be profitable as well.
Apart from the challenge tasks, we also ran code to extract a comparison of precipitation data for the observed months. 
<img src="https://github.com/ArmineKhanan/hawaii_climate_analysis/blob/main/images/June%20prcp.png" width ="300"> <img src="https://github.com/ArmineKhanan/hawaii_climate_analysis/blob/main/images/December%20prcp.png" width="300" />
