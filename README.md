# Capstone project IBM 

### A description of the problem and a discussion of the background
Taking a look at a bus stop in Toronto city, located at latitude = 43.649815 and longitude = -79.342163, we can see that there aren’t many places to eat. However, there are quite a few places that are related to sports such as gyms, Baseball fields and a lake for rowing. After doing some kind of exercise, we tend to get hungry. But the only options available are Coffee shops.

### A description of the data and how it will be used to solve the problem
The data is based of foursquare API explore feature, listing nearby spots to a Toronto bus stop. Taking into consideration that we use a radius of 800, there are 11 spots near the bus station. Only two of which are food related, a Tim Hortons, a famous Canadian Coffee shop, and a MountainView Fare trade Coffee. Using this information, the idea is to open a new restaurant that athletes can have a meal after a long workout session.

### Methology
First, we started by importing all the libraries necessary to run everything smoothly. Some of them are Pandas, Numpy, Request, Nominatim, Folium, etc..The next step was accessing Foursquare’s API by putting information relating to Foursquare's account.
Then, we set the location we want to analyse. In the case of the project it was latitude = 43.649815 and longitude = -79.342163.
The average was taken between the distance of the bus stop and the spots near. We got an average of 605.909.
We plotted the map using the Folium feature and assigned the data to dataframe_filtered. The dataframe contains information such as distance, name of the country, address, the name of the place , state, latitude and longitude.

### Discussion
From the results, we can see that the two nearest places to get food are Tim Hortons and MountainView fare Trade Coffee. However, these two places are still farther than average distance between the bus stop and near spots. The average distance is 605.9. Tim Hortons and MountainView fare Trade Coffee’s distance are respectively 637 and 609. If we take a closer look, it is not a really big difference. However, a restaurant much closer to the bus stop would be ideal. Something like 100 meters away would be the perfect distance for someone who just had a workout and wanted to grab a bite and get on the bus as quick as possible.

![](https://github.com/BrunoMO47/Capstone/blob/master/image/Screen%20Shot%202020-09-02%20at%2013.03.46.png)
