## Weather APi & Gmaps API :

In this repository you will find a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator.
you will find many scatter plots gives you the relationship between many factors and we run linear regression on each relationship.

You will find heat map that displays the humidity for every city and more.

---


## Written Observable Trends in the Data :
---
## Separate the cities into Northern Hemisphere and Southern Hemisphere 

### ( Our target is over randomly cities on the world  whose population is over 500)


 1. In the `chart Latitude vs. Max Temp` for `Northern cities` as we are heading `to the North` the `temperature decrease`. The `corraleation` is `negative linear relationship` because when varible x increase variable y decrease. The `r-value = -0.8` approximately `perfect negative linear relationship`.On the other hand `chart Latitude vs. Max Temp` for `Southern cities` we are heading from `South` to the `equator` and the `temperature increase`. `r value=0.5` `intermediate positive relationship`. 

    * Why this trend is occurring:

        As we can see in the picture below...




        [world_map.png](weatherpy/output_data/world_map.png)                     
        credit for: https://www.shsu.edu/~dl_www/bkonline/131online/f02latitude/02index.htm



        `most` of the `cities` distrbuited in the `North` `compare` to the `South` that most of the area is `Ocean` so we can see `more reslut` indicates the temperature from the `North`.Now why on `point 0 high temperature` because the `sun` is always directly `overhead` at the `equator`.

2. Now for chart `City Latitude vs. Humidity` for `Northern` cities as we are `heading` to the `North` thers is `increase` in `humidity` as `the same` in `chart City Latitude vs. Humidity` for `Southern` citites.The `corraleation` for `Northern` citites and `Southern` cities `are positive` linear realtionship. `r value= 0.39` for `Northern` and `0.38` for `Southern` cities so we have `weak positive relatioship`.

    * Why this trend is occurring:

        When `temperature is high` so the `tend` to be `more humid` than cool places then because of that when we are heading to the North from Souchern cities the humidity increase but there is `other factor` effect on the humidity, this one is `water evaporates` in a given area, the more water vapor rises into the air because of that `r value` we got `tend to weak relationship` between latitude vs humidity.

3. `City Latitude vs. Wind speed` chart for `Northern` cities  and `City Latitude vs. Wind speed` chart for `Southern` cities we have `very weak relationship`. They have `r vlaue = 0.13` for `Northern` cities and `-0.24` for `Southern` cities.

    * Why this trend is occurring:

        There are many `factors effect` on Wind speed like `pressure gradient` `Rossby waves and jet streams`, and `local weather conditions`, but the `latitude not one` of them because of that the `relation is very weak`.   

