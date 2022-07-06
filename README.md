# Citi Bike Analysis
Tableau visualisation is available here: https://public.tableau.com/app/profile/chris2700/viz/NYCitiBike21to22/TripTimeByMemberRides?publish=yes

Background: The analysis attempts to uncover unexpected phenomena behind the rideshare program of New York Citi Bike. The analysis is based on 12 months (June 2021 to May 2022) trip history. PowerQuery is utilised to consolidate the 12 CSV files into a single data source.

Dashboard #1: Trip Time (in minutes) based on memberships and type of ride
A calculated field is created to find the length of each trip: Trip Time = (End Time - Start Time) x 24 x 60
Unexpected Phenomena: Casual users' total and average length of trip is higher than permanent users (members). Classic bike is very popular among "members", while "casuals" are also willing to utilise docked bike and electric bike.

Dashboard #2: Stations popularity
Unexpected Phenomena: Very distinct type of users is found between the popular stations. Casual users is more popular in Hoboken area (northern side of the map), while member users is more popular is Jersey City.
