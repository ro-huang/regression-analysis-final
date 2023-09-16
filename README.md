# Final project for Regression Analysis
Final Project for STAT210 Regression Analysis. Won 3rd Prize in the [USPROC](https://www.causeweb.org/usproc/) June 2023 Intermediate Statistics Class Project competition. The competition was sponsored by the American Statistical Association (ASA) and the Consortium for Advancement of Undergraduate Statistics Education (CAUSE). See project background [here](https://www2.stat.duke.edu/courses/Spring23/sta210.001/slides/individual.html).

# Codebook 
The following are some key variables included in our analysis:

Race Background Information

-   *race_type*: the type of race (5k vs. Marathon)

-   *sex*: the sex of runners running that competition (Men, Women, or Both)

-   *year*: the year the race was hosted on

Weather Variables

-   *air_temp*: in Celsius, temperature in air at the halfway point of the race

-   *adj_wind_speed*: in meters per second, wind speed at the halfway point of the race adjusted for height above the ground and air friction coefficient (i.e., large city with tall buildings)

-   *relative_humidity*: in %, relative humidity at the halfway point of the race

Race Result Variables

-   *first_place*: the finish time for the first place runner

-   *world_record*: world record for this kind of race during that year

Created Variables

-   *world_first_pct* $(\frac{\text{world record time - first place time}}{\text{world record time}})$: this variable looks at the difference between the world record time in minutes and first place time in minutes as a percentage of world record time. This variable was created to provide a comparable outcome variable across 5k and marathon times.

