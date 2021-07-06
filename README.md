# Ford go bike trips Feb 2019 San Francisco

# About the dataset

What is the structure of your dataset?
There are 183,412 trips in this dataset in Feb 2019 in San Francisco with information of each trip's starting station (station name, id, longtitude, latitude), end station (station name, id, longtitude, latitude), start time (date & hour), end time (date & hour), duration, who the rider was (their gender, age, user type), and which bike it was (shared bike or not, and bike id). There are 329 stations in San Francisco, and a total of 4646 bikes.

What is/are the main feature(s) of interest in your dataset?
1) I'm interested in investigating which stations are operating at their max capacity, and which stations are operating at a lost.
2) Besides that, I want to know which days and hours are the busiest and least busy, and some strategies to maximize the "dead hours" (least busy).

What features in the dataset do you think will help support your investigation into your feature(s) of interest?
1) I think that other features like duration span and number of bikes are parked at each stations would be good indicators to determine which stations are operating at their fullest capacity or at a loss.
2) I think other demographic data such as member's birth year, gender, and user type can help me understand the peak days and hours better.

# Key findings

###  Times

Thursdays have highest number of trips with a total of 67,461. Follwing by Tuesdays with 61,239 trips. On Mondays, Wednesdays and Fridays have somewhere from 51,000 to over 55,000 trips.

Saturday and Sunday have significantly lower trips than weekdays with only 30,818 and 31,046 trips respectively which are half of the total trips on Tuesdays and less than half of total trips on Thursdays. 

The most common start and end hours in the morning is from 8 to 9, and in the afternoon is from 17 to 18 also known as the rush hours. This again confirms the theory that most of the riders are professionals who use Ford bikes to commute to work. 

Most trip starts at 08 in the morning and again at 17 in the afternoon, following by trips start at 09 and 18. Tuesday and Thursday have the highest number of trips. Saturday and Sunday have the lowest number of trips.

Most trip starts at 08 in the morning and again at 17 in the afternoon, following by trips start at 09 and 18. Tuesday and Thursday have the highest number of trips. Saturday and Sunday have the lowest number of trips.

### Demography

The total number of male users of all age groups (including Silent Generation) is 13,0358 which is almost 3.5 times higher than female users, and is 36 times higher than other gender users.

Number of total subscribers are 158,162 which is 9.5 times higher than customers at 16,615. This is a good sign because subscriber has higher life time value for the service than the customer as the subscriber usually use this service on a day basis. Similar to that, most of the bikes are not shared which means higher value for Ford.

Gen Y Subscriber is the largest group in the heatmap with 102,911 users, 104,493 users in Gen Y don't share a bike and 83435 of them are males.

Come second across all categories are Gen X users with 27,250 male users, 6,843 female users, 869 other users, a total account of 31,930 subscribers, 3,132 cutomers, 31,832 not shred bike and 3230.

The third most popular group is Gen Z. One theory why Gen Z is not the popular users yet is that not many Gen Z are professionals who work in downtown San Francisco. However, Gen Z users may be blooming in couple years. One way to examinize this is to look at the growth of Gen Z users over the year.

### Location

These are the 7 most profitable stations of Ford Go Bike with over 5000 visits.
San Francisco Caltrain Station 2 (Townsned St at 4th St), Market St at 10th St, Montgomery St BART Station (Market St at 2nd St), San Francisco Ferry Building (Harry Bridges Plaza), Berry St at 4th St, Powell St BART Station (Market St at 4th St), and San Francisco Caltrain (Townsend St at 4th St).
Ford may want to collect more data on the wait time to get a bike at these top 7 most visited stations to see if there are longer wait times for users. If there're, Ford may want to add more bikes to these stations.

These are the 14 least profitable stations of Ford Go Bike with less than 50 visits.
San Pedro St at Hedding St, Williams Ave at Apollo St and Foothill Blvd at 42nd Ave, 23rd Ave at Foothill Blvd, Backesto Park (Jackson St at 13th St), Farnam St at Fruitvale Ave, 26th Ave at International Blvd, 23rd Ave at Foothill Blvd, Backesto Park (Jackson St at 13th St), Leavenworth St at Broadway, Taylor St at 9th St, Farnam St at Fruitvale Ave, Parker Ave at McAllister St, Willow St at Vine St, Palm St at Willow St, 21st Ave at International Blvd, and 16th St Depot.

The most popular route is from station 81 - Berry St at 4th St- to station 15 - San Francisco Ferry Building- in Feb 2019 with 337 trips.
The second popular route starts at station 58 - Market St at 10th St - and ends at station 21 - Montgomery St BART Station.
The third popular route is also starts at station 58, but ends at station 3 which is Powell St BART Station.
The fourth popular route again starts at station 58, but ends at station 67 which is San Francisco Caltrain Station 2

The route that has longest duration on average is from station 81, Berry St at 4th St, to station 67, San Francisco Caltrain Station 2 with 563.5 seconds.
Interestingly, come second is a round trip starts and ends at the same station 16, Steuart St at Market St, with the average time span of 3426 seconds.
Third longest duration route is from station 30, San Francisco Caltrain, to station 67, San Francisco Caltrain Station 2, with 3299 seconds.

# Further possible investigations
Although in this project, I chose to break down the data set into three areas - demography, time and location - to explore, there are interesting paths you can go when investigating this data.

One path would be looking across three areas I investigated above. Here are some ideas:
1) Find the peak times of the most popular stations.
2) Look at which user type uses the Ford Go Bike service more each day. Maybe there are more customers riding the bikes in the weekend.
3) Look at which stations have the highest Baby Boomers or Gen Z, and make suggestions if Ford should run some local marketing campaigns there

# This repository
1) Exploratory ipyn file
2) Explanatory ipyn file
3) Interactive exploratory file
4) Interactive explanatory file
