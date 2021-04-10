# World_Weather_Analysis
Plotting the relationship between latitude and weather for cities round the world using Python , Pandas and APIs

## Overview
Plan my Trip is a top travel technology company that specializes in internet-related services for the hotel and lodging industry. 
Jack who is the head of analysis, wanted us to help to collect data and present it to customers via the search page, which they will then filter based on their preferred travel criteria to find their ideal hotel anywhere in the world.
We used Jupyter Notebook, in the CityPy module to get random cities Latitude and longitude. Performed request on the open weather map API and retrieved the JSON weather data from these cities. The weather data was added to a pandas data frame and used Matplotlib to create a series of scatter plots to show the relationship between latitude and longitude.
This data helped the Team predict the best time of the year for people to plan their vacations. 

## Challenge Overview
Jack loved the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data. We will have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

## Challenge Summary 
- We generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and performed an API call with the OpenWeatherMap. In addition to the city weather data we gathered in this module, used API skills to retrieve the current weather description for each city. Then, created a new DataFrame containing the updated weather data and saved it as a CSV file.

![image](https://user-images.githubusercontent.com/78935551/114281104-6fbdeb00-9a0a-11eb-8bc8-0b82ec0c2243.png)


- We created a customer Travel Destination Map using input statements to retrieve customer weather preferences, then used those preferences to identify potential travel destinations and nearby hotels in Brazil. Showing those destinations on a marker layer map with pop-up markers.

![image](https://user-images.githubusercontent.com/78935551/114281111-7fd5ca80-9a0a-11eb-9e34-935251eee7d4.png)

- We also created a Travel itierary Map using Google Directions API that shows the route between four cities chosen from the customer’s possible travel destinations. Then, created a marker layer map with a pop-up marker for each city on the itinerary.

#### This is the directions layer map :

![image](https://user-images.githubusercontent.com/78935551/114281121-97ad4e80-9a0a-11eb-9df9-c4f799bf547f.png)


#### This is the marker layer map with a pop-up marker for each city :

![image](https://user-images.githubusercontent.com/78935551/114281124-a0058980-9a0a-11eb-9a3b-6b486cb3afc1.png)







