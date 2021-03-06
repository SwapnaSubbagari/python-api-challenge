# python-api-challenge
# Background
Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"
Now, we know what you may be thinking: "Duh. It gets hotter..."
But, if pressed, how would you prove it?

# Process
Part I - WeatherPy
In this example, you'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, you'll be utilizing a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.
Your first requirement is to create a series of scatter plots to showcase the following relationships:
Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude
After each plot add a sentence or too explaining what the code is and analyzing.
Your second requirement is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude - Please refer to the screenshots in the Screenshots folder.

Southern Hemisphere - Temperature (F) vs. Latitude - Please refer to the screenshots in the Screenshots folder.

Northern Hemisphere - Humidity (%) vs. Latitude - Please refer to the screenshots in the Screenshots folder.

Southern Hemisphere - Humidity (%) vs. Latitude - Please refer to the screenshots in the Screenshots folder.

Northern Hemisphere - Cloudiness (%) vs. Latitude - Please refer to the screenshots in the Screenshots folder.

Southern Hemisphere - Cloudiness (%) vs. Latitude - Please refer to the screenshots in the Screenshots folder.

Northern Hemisphere - Wind Speed (mph) vs. Latitude - Please refer to the screenshots in the Screenshots folder.

Southern Hemisphere - Wind Speed (mph) vs. Latitude - Please refer to the screenshots in the Screenshots folder.

After each pair of plots explain what the linear regression is modeling such as any relationships you notice and any other analysis you may have.
Optional You will be creating multiple linear regression plots. To optimize your code, write a function that creates the linear regression plots.
Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.


Part II - VacationPy
Now let's use your skills in working with weather data to plan future vacations. Use jupyter-gmaps and the Google Places API for this part of the assignment.
Note: if you having trouble displaying the maps try running jupyter nbextension enable --py gmaps in your environment and retry.
Create a heat map that displays the humidity for every city from the part I of the homework.
Narrow down the DataFrame to find your ideal weather condition. For example:
A max temperature lower than 80 degrees but higher than 70.
Wind speed less than 10 mph.
Zero cloudiness.
Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.
Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.

# Screenshots:
Please refer to the screenshots in the Screenshots folder.
