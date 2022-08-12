# python-api-challenge
Taking all we've learned so far we were tasked with answer these questions:
"What is the weather like as we approach the equator?" And if we know that it gets hotter the closer to the equater, how do we prove that?
First, for our WeatherPy file we needed to fulfill these requirements:
Create a series of scatter plots to showcase the following relationships:
Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude
And then, the second requirement was to compute the linear regression for each relationship. And, separating the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).
Afterwhich, we created VacationPy to plan a future vacation in a desired destination based on weather. To complete this part of the assignment, I was tasked with creating a heat map that displays the humidity for every city from Part 1 (WeatherPy). Then I had to narrow down the DataFrame to find the ideal weather condition. For example:
A max temperature lower than 80 degrees but higher than 70
Wind speed less than 10 mph
Zero cloudiness
And then finally, drop any rows that don't satisfy all three conditions, to be sure that the weather is ideal.
