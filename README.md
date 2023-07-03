# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
<<<<<<< HEAD
<<<<<<< HEAD
My goal was to find a relationship between the number of Points of Interests in the area and the number of bike stations: Points of Interests or restaurants have a higher rating with nearby bike stations. 
 

## Process
1.Choose a city from [CityBikes](https://citybik.es/). Request information from their API.
	*  I choose Vancouver. It has almost 250 stations and a total of 4,563 available bikes

2. Connect to Foursquare and Yelps API to get the locations of * Restaurants or bars and * Various POIs (points of interest) of your choice
	* Connecting to the Yelp API was the most tedious. I did not realize very iteration was considered a call, so I kept running out of calls. 
 
3. Create a data frame and compare results. Which gave the most complete information. 
	*  Yelp's API provided more information; however, the Foursquare API was easier to work with and I was able to discover more about the data with multiple inquires. On the other hand, I faced was with the limited calls available in Yelp's API.

4. Use data visualization to explore data.
	* Since we had coordinates to work with, I choose to create a folium map to show the relationship between the number of Points of Interests in the area and the number of bike stations. 

5. Create a SQLite database, store collected data and validate your results. 
	* I was able to create a SQLite database and upload the collected data. I validated this by confirming I had the same number of rows. 

6. Build a model and derive insights.
	*  Aside from my challenges with the Yelp API, this was my other biggest challenge. Although, it did not take a lot of time, it did not give a favorable result. The p-values and the R-squared values did not provide an output; therefore, the model could not find a meaningful conclusion from the regression analysis. 

## Results
I found that I need more data to review. Unfortantely, with the limit amount of time and calls for Yelp, it was a challenge to get and filter more meaningful data. When cleaning my ratings column, I did not realize how many NaN values were present. Orignally, I was hoping find a relationship between the POI ratings and number of bike stations. I had believe people would find it easier to get to without a car due to access to a city bike. 

## Challenges 
My biggest challenge was figuring out where to start. Data wrangling is still a very new concept for me. Yelp was also a huge time suck for me. A lot of my time was waiting for calls to be available. Then checking to see if I had the right data. 

## Future Goals
* If I had more time, I would have dug deeper and looked for more tangible data which could have helped my regression model to prove hypothesis. 
* I would also have spent more time customizing the folium map to make it more visually appealing. 
* I would have also asked for more direction or asked more questions on how APIs worked. ie: each iteration = a call. 

=======
(fill in your description and goals here)
=======
My goal was to find a relationship between the number of Points of Interests in the area and the number of bike stations: Points of Interests or restaurants have a higher rating with nearby bike stations. 
 
>>>>>>> 627ae40a1fc450e1ea034298a180edec8f84abf3

## Process
1.Choose a city from [CityBikes](https://citybik.es/). Request information from their API.
	*  I choose Vancouver. It has almost 250 stations and a total of 4,563 available bikes

2. Connect to Foursquare and Yelps API to get the locations of * Restaurants or bars and * Various POIs (points of interest) of your choice
	* Connecting to the Yelp API was the most tedious. I did not realize very iteration was considered a call, so I kept running out of calls. 
 
3. Create a data frame and compare results. Which gave the most complete information. 
	*  Yelp's API provided more information; however, the Foursquare API was easier to work with and I was able to discover more about the data with multiple inquires. On the other hand, I faced was with the limited calls available in Yelp's API.

4. Use data visualization to explore data.
	* Since we had coordinates to work with, I choose to create a folium map to show the relationship between the number of Points of Interests in the area and the number of bike stations. 

5. Create a SQLite database, store collected data and validate your results. 
	* I was able to create a SQLite database and upload the collected data. I validated this by confirming I had the same number of rows. 

6. Build a model and derive insights.
	*  Aside from my challenges with the Yelp API, this was my other biggest challenge. Although, it did not take a lot of time, it did not give a favorable result. The p-values and the R-squared values did not provide an output; therefore, the model could not find a meaningful conclusion from the regression analysis. 


## Results
I found that I need more data to review. Unfortantely, with the limit amount of time and calls for Yelp, it was a challenge to get and filter more meaningful data. When cleaning my ratings column, I did not realize how many NaN values were present. Orignally, I was hoping find a relationship between the POI ratings and number of bike stations. I had believe people would find it easier to get to without a car due to access to a city bike. 


## Challenges 
My biggest challenge was figuring out where to start. Data wrangling is still a very new concept for me. Yelp was also a huge time suck for me. A lot of my time was waiting for calls to be available. Then checking to see if I had the right data. 


## Future Goals
<<<<<<< HEAD
(what would you do if you had more time?)
>>>>>>> 6eed944e96fb0005ddd55c40e4f5164ab6b46634
=======
* If I had more time, I would have dug deeper and looked for more tangible data which could have helped my regression model to prove hypothesis. 
* I would also have spent more time customizing the folium map to make it more visually appealing. 
* I would have also asked for more direction or asked more questions on how APIs worked. ie: each iteration = a call. 

>>>>>>> 627ae40a1fc450e1ea034298a180edec8f84abf3
