# bikesharing
Pandas (Python), Jupyter Notebook, Tableau Public

[Link to the practice Tableau file created inside of the lesson modules](https://public.tableau.com/app/profile/stefan.williams/viz/NYCCitibikeVisualizationPractice/NYCStory)

[Link to the module challenge Tableau presentation](https://public.tableau.com/app/profile/stefan.williams/viz/NYCCitibikeAnalysis_16828047419430/FinalPresentation?publish=yes)
<br>

[Stack overflow resource used to convert Dataframe column to datetime format](https://stackoverflow.com/questions/44118395/python-pandas-convert-seconds-to-time-hhmm)

[Link to the Citi Bike trip data, 201908 was the specific file used](https://s3.amazonaws.com/tripdata/index.html)

## Overview of bikesharing

#### The purpose of this analysis is to prepare a Tableau analysis on public data for NYC Citi Bike users. Several analyses were performed on the data for the challenge, as well as a story to summarize the visualizations.

## Results

#### This is a basic visualization showing the relationship between number of users and trip duration. Most users seem to checkout their bikes within an hour, with the wide majority of those users being before 20 minutes.
![vis1](https://i.gyazo.com/81ffdba3580a500270fe2c6ae2873a8b.png)
#### This is the same visualization as before, but with the users filtered by gender. Checkout times remain similar, and males seem to use the bikes more often. 
![vis2](https://i.gyazo.com/a602515223c86e010e4a08f319f1d0f6.png)
#### This is a heatmap of the general trips taken by weekday and hour. 6 AM to 8 PM are generally more active times, with weekdays being particularly active.
![vis3](https://i.gyazo.com/e8a1a4ac3e227974ed88cfccc0541866.png)
#### This heatmap follows the same trend of the previous, but further illustrates how males make up more of the total trips taken. The screenshot doesn't do it much justice, but the users of "Unknown Gender" do not add any outliers that did not exist in the previous visualization.
![vis4](https://i.gyazo.com/61077d653890f2d5d57657b909ad965a.png)
#### This is another heatmap dividing users by Nonsubscriber/Subscriber and Gender. Subscribers make up most of the user base, with male subscribers leading. Non subscribers seem to use their bikes more on the weekends, hinting to an idea that non subscribers could be tourist/guest traffic.
![vis5](https://i.gyazo.com/ce9abf55b333c202c87b5a0216f8ff1f.png)
#### This is a graph of starting locations for Citi Bike usage. It shows a lot of evidence for user traffic and possible tourist traffic, with a good chunk being in what can assumed to be the busier city centers.
![vis6](https://i.gyazo.com/0cc80944a4656d23c0cd44aee1c1c8ef.png)
#### This last visualization used is a pie graph showing total users by gender. While it is already known that most of the reported users are male, given that 3 of the previous visualizations have a gender filter, it gives a breakdown of exactly how many and what percentage of the users are each gender for the sake of clarity.
![vis7](https://i.gyazo.com/e049321221ed446dcbd0567458d0114e.png)

## Summary

#### In summary, using the visualizations, the primary hours of use for the bikes seem to be between 6 AM to 8 PM. Location and time of year can greatly change this data as the weather and time of sunrise/sunset changes. This data is limited, as this is only for New York City. Not all locations have active bike sharing services, but this can be used as a metric for future implementing of these services in new locations. Less active times seem to be a great time to perform maintenance and bike repairs.

#### More males use these bikes than females. While males are not actually more active than females, and most bikes are designed for unisex and general purposes, it can be assumed that females are less likely to perform an activity that has them riding through busy city streets by themselves. However, this is only an assumption based on safety reasons and trends of gender-motivated crime/violence, and there is no concrete data in this example to prove that. 

#### There are two additional visualizations I would perform on this data just from what I have seen so far. 
- I think there could definitely be a relationship between tourists/guests being "Customers" instead of "Subscribers" to the Citi Bike bike sharing service, and I would like to compare the numbers of Customers vs Subscribers. Substituting "Gender" with "Usertype" in these previous visualizations may show different trends.
- Start and end stations were also not explored in any of the visualizations performed. While population by location definitely varies by city, I believe that more popular stations could hint at more "tourist-y" areas and perhaps have a correlation with nonsubscribers. This can be used to support a claim that developing a bike sharing service in an area boosts tourism.
