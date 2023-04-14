# (Ford GoBike System Data)
## by (turki alothman)


## Dataset





This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
eindividual ride contain the folowing info :<br>

-duration_sec
-start_time
-end_time
-start_station_id
-start_station_name
-start_station_latitude
-start_station_longitude
-end_station_id
-end_station_name
-end_station_latitude
-end_station_longitude
-bike_id 
-user_type
-member_birth_year
-member_gender
-bike_share_for_all_trip

no need to describe each column since they are very clear and describe them self.

data wrangling:

-all unnecessary columns were dropped

-each rows with one missing value at least  was dropped

-duration unit was changed from second to minute

-date data type changed from from float integer




## Summary of Findings


I am very interested to figuring out the what factor that make the rider spend more time and what feature that make people rent a bike(what factor will increase the number of individual rides) .so I asked 11 questions in order to find all factors or relationships thats make the indavuals spend more time or increase the number of individual rides.

here some factors and relationships I found:

1-genders can be a factor that increase the number of individual rides since 74.6% of the individual rides are males.

2-the user type is important factor that increase the number of individual rides since 90.5% of the individual rides are subscribers.

3-the station can could be a factor that increase the number of individual rides since that some stations are more popular than others. And that there are stations that are preferred over others.

4-most of the individual rides are young people.

5-user type(subscriber or customer ) plays a role of individual ride duration. since on avarege, customers spend more time than subscriber.

6-the gender can effect in individual ride duration.

 
(1,4,5) will be included in explanatory presentation


## Key Insights for Presentation

1-genders can be a factor that increase the number of individual rides.

2-most of the individual rides are young people.

3-user type(subscriber or customer ) plays a role of individual ride duration.

these three finding will be explained and displayed in my presentation. since all encodings were performed in exploration stage.

here some steps to change the design for each plot:

1-(x,y)labels will be diplayed
2- title will be displayed
3-a number will be diplayed on a top of each bar in barchar




> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.