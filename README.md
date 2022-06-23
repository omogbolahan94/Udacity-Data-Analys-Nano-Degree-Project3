# Ford GoBike System
## by Olatunji Gabriel
### 23rd June, 2022


## Dataset
* The February 2019 Ford GoBike System data contains informations about users trip.
* The following are the features from the dataser:
    *  duration_sec             
    *  start_time               
    *  end_time                 
    *  start_station_id         
    *  start_station_name    
    *  start_station_latitude   
    *  start_station_longitude 
    *  end_station_id           
    *  end_station_name     
    *  end_station_latitude  
    *  end_station_longitude    
    *  bike_id             
    *  user_type            
    *  member_birth_year     
    *  member_gender    
    *  bike_share_for_all_trip
* During the wrangling process, i performed the following data cleaning:
* Converted type of `start_time` and `end_time` features from object type to pandas datetime type.
* Converted type `user_type`, `member_gender` and `bike_share_for_all_trip` from object type to categorical type since they 2, 3 and 2 unique values respectively.
* Due to outliers in the `duration_sec` feature, every values above the value gotten from the addition of the 75th percentile value and 1.5 times the inter-qauntile range of the feature are set to that value.


## Summary of Findings
The following are the key findings from my analysis of the Ford GoBike dataset is:
* There are up to 19868 customer types and over 163544 subcriber type.
* Mostly of the bike users are male.
* Most of the bike users do not share their bike. Of all the 183411 users, only 17359 users share their bike.
* Most of the bike users were born between the year 1988 and 1998.
* Most of the bike users journeyed between 301 an 361 seconds.
* Three most used stations are: Market St at 10th St, San Francisco Caltrain Station 2 (Townsend St at 4th St) and Berry St at 4th St.
* The five (5) least used stations are: 16th St Depot', '21st Ave at International Blvd, Palm St at Willow St, Parker Ave at McAllister St, Willow St at Vine St, Taylor St at 9th St
* The most busiest period of time is 8 A.M and 5 P.M. Other busy times are 8 A.M, 9 A.M, 6 P.M and 7 P.M
* Most non subscribers tends to be active between 10 A.M and 4 P.M.
* It is observed that female users used the bike for a longer average period of time than men.
* For all the gender, most cutomers user type spend more time on a trip.
* The average trip for a female customer is way more than any other gemder type


## Key Insights for Presentation
The following are the key insights from the presentation of my analysis:
* It can be seen that mojority of the users are subscribers.
* Most of the bike users are male.
* Most of the bike users do not share their bike. Of all the 183411 users, only 17359 users share their bike.
* Most of the bike users were born between the year 1988 and 1998.
* The top five (5) most popular start stations are:
    * Market St at 10th St
    * San Francisco Caltrain Station 2 (Townsend St at 4th St)
    * Berry St at 4th St
    * Montgomery St BART Station (Market St at 2nd St)
    * Powell St BART Station (Market St at 4th St)
* The follow are the list of the top 5 least used stations:
    * 16th St Depot
    * 21st Ave at International Blvd
    * Palm St at Willow St
    * Parker Ave at McAllister St
    * Willow St at Vine St
* The most busiest period of time is 8 A.M and 5 P.M. Other busy times are 8 A.M, 9 A.M, 6 P.M and 7 P.M
* Average duration of all customer users of any gender is more than that of subscribed user.
* Most non subscribers tends to be active between 10 A.M and 4 P.M.