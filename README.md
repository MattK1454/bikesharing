# Bike Sharing Project

## Overview

This analysis used bike sharing data from the Citi Bike sharing program in New York City to analyze how the program works and its viability to be implemented in Des Moines, Iowa.

## Results

[NYC Citi Bike Project Dashboard](https://public.tableau.com/profile/matthew.kaufmann#!/vizhome/NYCCitiBikeProjectDashboard/NYCCitiBike) 
- Dashboard visualization for the Citi Bike Project.

[NYC Citi Bike Project Story](https://public.tableau.com/profile/matthew.kaufmann#!/vizhome/NYCCitiBikeProject_16098901306970/NYCCitiBikeStory)
- Story for the NYC Citi Bike Project.

[NYC Citi Bike Challenge Story](https://public.tableau.com/profile/matthew.kaufmann#!/vizhome/NYCCitiBikeChallenge_16098898415460/NYCCitibikeStory)
- Story for the NYC Citi Bike Challenge analysis.

![Average tripduration](https://github.com/MattK1454/bikesharing/blob/main/images/Average%20tripduration.png)

This visualization looks at the average trip duration vs birth year. If the trend of the data is prioritized then there is an observation of increased trip duration as the age of the user moves towards younger users. This suggests people born more recently will utilize the bike for longer periods. The time measure for trip duration is in seconds. The birth year begins at 1880 which can not be accurate, if we assume the data was recorded with errors but the overall trend is accurate even with the errors, then the analysis of younger users use the bikes for longer holds for a point of interest in the project analysis.

![Bike Utilization](https://github.com/MattK1454/bikesharing/blob/main/images/Bike%20Utilization.png)

This visualization, at first glance, is difficult to understand. What is displayed here are details pertaining to the amount of use each bike received in the month of August in 2019. Each dot represents a bicycle in the Citi Bike sharing program. The size of the dot is in relation to the amount of use in seconds the bike experienced during the month of August. The larger the dot, the more the bike was used. This data suggests tracking the bikes most often used may allow for a deeper understanding of some of the factors encouraging use of the bike sharing program.

![Checkout time for Users](https://github.com/MattK1454/bikesharing/blob/main/images/Checkout%20Time%20for%20Users.png)
This visualization details how many bikes are checked out for trips by each hour. The visualization shows approximately 2900 bikes are checked out during the 5am hour. The visualization then shows bikes begin to be returned to stations after the 5am hour. This suggests morning trips are far more common than evening trips for the bike share program.

![Checkout times by gender](https://github.com/MattK1454/bikesharing/blob/main/images/Checkout%20Times%20by%20Gender.png)

This visualization was designed to look at bike checkouts by gender by hour. What the data shows here is the majority of users of the system are male users. The data shows males checked out over 2000 bikes for trips by 5am. This visualization can help calculate the percentage of use by gender by hour time. This information may help focus where advertising dollars can be spent to optimize implementation in an alternate city. The data suggests adversting to young males using the bike sharing program for moring communtes may be the best way to initially spend advertising dollars should the program be implemented in Des Moines, Iowa.

![Trips by gender (Weekday per hour)](https://github.com/MattK1454/bikesharing/blob/main/images/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)

This visualization futher helps to break down, by hour, the periods of highest use of the bikes in the program by gender. The darker the color of the rectangle, the higher return of bikes to the program by that gender in that hour. This data suggests highest use hours for male, female, and unknown are the concluded between 7am and 9am as well as from 5pm to 8pm. This data will help to known when the most amount of bikes will need to be available and how to advertise for most likely use.

![Trips by weekday per hour](https://github.com/MattK1454/bikesharing/blob/main/images/Trips%20by%20Weekday%20per%20Hour.png)

This data details the use of the program by weekday by hour. This will help the program to be designed in a way to account for when bikes are most used by weekday. This data can help to show when bikes will be available for use and when bike repairs can be performed to maintain resources for use. Data here shows weekdays from 7am to 10am and 5pm to 8pm tend to be the highest periods when bikes are returned to stations. There is also noticable return of the bikes on the weekends during the morning (7am to 10am) and evening (5pm to 8pm). This data shows most bikes will be returned roughly consistenly during the midday periods of the weekend. All of this data suggests morning repairs on weekends and during midday and evenings on weekdays.  

![User trips by gender by weekday](https://github.com/MattK1454/bikesharing/blob/main/images/User%20Trips%20by%20Gender%20by%20Weekday.png)

The final visualization shows how each type of customer (infequent user vs. subscriber) uses the program with respect to each day of the week. Shown here is evidence that male subscriber customers use the system the most particularly on Thursdays, Fridays, Mondays, and Tuesdays. Female subscribers also take more trips than infequent users. This data suggests designing the program to encourage subscribership from the start would be supported by the data.

## Summary

The analysis for the Citi Bike sharing program from the month of August in 2019 shows the bike sharing program is very active in New York City. Looking at the stories and dashboards linked to above, evidence suggests a consistent level of use especially around sites strongly linked with high population areas/tourist locations. The data also demonstrates a high level of use for particular bikes shown by the average tripduration visualization. Data also suggests there is an upward trend for bike sharing as age decreases. Data also suggests men make the most use of the bike sharing program particularly from the 5am to the 8am hours. There is also evidence suggesting the most bike trips take place on weekdays prior to 8am to 9am, 5pm to 7pm, and Saturdays from 10am to 6pm. With the average trip duration trending upward for younger generation, it is reasonable to state any program implimented would need to be done in a location with a younger male population and within tourist locations. The data suggests adversting to young males using the bike sharing program for moring communtes and returning home in the evening may be the best way to initially spend advertising dollars should the program be implemented in Des Moines, Iowa. There is also evidence to show repairs for bikes should be setup to occur in the early moring hours and in the evenings and well as during midday on weekdays. It should be noted the data suggests any implimentation of this bike share program should be designed to encourage subscribership from the onset as subscribers are the heaviest users of the program.


Two possible visualizations that could be added to this analysis are:
* Customer type by gender
* Customer type by age and average trip duration

## References

1. Module 14 Challenge. (n.d.). Retrieved January 05, 2021, from https://courses.bootcampspot.com/courses/453/assignments/6111?module_item_id=91338
