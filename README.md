# AppliedDS_Capstone_Project_TheBattleofNeighborhoods

# Introduction
This final project explores the best locations for Japanese restaurants throughout the city of New York. As New York is the most diverse city in the US and probably in the entire world as well, it has a long tradition of different ethnical restaurants. Now when the idea of a healthy lifestyle conquered the minds of people all over the country, Japanese restaurants became extremely popular, as they offer a healthy alternative to regular American eating habits. That's why potentially the owner of the new Japanese restaurant can have great success and consistent profit. However, as with any business, opening a new restaurant requires serious considerations and is more complicated than it seems from the first glance. In particular, the location of the restaurant is one of the most important factors that will affect whether it will have success or a failure. So this project will attempt to answer the question “Where should the investor open a Japanese Restaurant?”

# Data
In order to answer the question, the required data includs: New York City neighborhoods, boroughs to include boundaries, latitude, longitude, restaurants, and restaurant ratings and tips. New York City data containing the neighborhoods and boroughs, latitudes, and longitudes will be obtained from the data source: https://cocl.us/new_york_dataset. All data related to locations and quality of Japanese restaurants will be obtained via the FourSquare API utilized via the Request library in Python.

# To solve the problem
• Data will be collected from https://cocl.us/new_york_dataset and cleaned and processed into a dataframe.
• FourSquare be used to locate all venues and then filtered by Japanese restaurants. Ratings, tips, and likes by users will be counted and added to the dataframe.
• Data will be sorted based on rankings.
• Data will be visually assessed using graphing from Python libraries.
