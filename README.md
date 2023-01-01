# Ford GoBike System Data Exploration
## by Hichem Dridi


## Dataset

This data comes from a bike sharing system known as **Ford GoBike System Data**. This is information for *183,412* trips covering the greater San Francisco Bay Area. The dataset can be found and downloaded from [Kagggle](https://www.kaggle.com/datasets/ahmedmohameddawoud/ford-gobike-system-data).


## Summary of Findings

Data was collected from stations across San Francisco and nearby cities like Berkeley, Oakland and Emeryville during the month of February. At that time most bicycles were used by subscribers, I also found that this system of self-service bicycles was mainly preferred by men and young people.

The duration of bicycle trips takes a very wide interval, from one minute to almost a day, with a logarithmic transformation I found that the majority of trips were around ten minutes long and 96% of them took less than one half hour. The duration is highly dependent on the day and time of the ride, weekdays are associated with short daytime rides, while longer bike rides are on weekends in the early morning and mid-day . Another interesting result is that the duration of the bicycle journey depends on the gender of the user, for example men make on average very short journeys for different age categories.

The time-day combination not only influences the duration of bike rides, but also the use of bicycles. Bikes are heavily used around 8am and 5pm on weekdays, but on weekends there is average daytime use. Weekends also see a change in the routes taken by users, on Sundays for example a large number of bicycles are transported from the nearest station to Golden Park.


## Key Insights for Presentation

For the presentation, I start with a description of the users of this bike sharing system (gender, age and type of user) and an overview of the location of the stations, followed by the distribution of the use of the bicycle between cities.

Next, I introduce the distribution of values of the duration feature, and then show in two separate heatmaps the effect of day and time on bicycle use and trip duration.

The last part is specified to identify who takes the longest bike rides in terms of duration, and this was achieved by studying the interaction between feature duration and user-related fields.