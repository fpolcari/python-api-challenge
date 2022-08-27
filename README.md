# python-api-challenge
Taking all we've learned so far we were tasked with answer these questions:
"What is the weather like as we approach the equator?" And if we know that it gets hotter the closer to the equater, how do we prove that?
First, for our WeatherPy file we needed to fulfill these requirements:
Create a series of scatter plots to showcase the following relationships:
Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude
Below is a screenshot of our temperature versus latitude plot:
<img width="1050" alt="Screen Shot 2022-08-27 at 4 47 33 PM" src="https://user-images.githubusercontent.com/106457512/187047503-d73c65d3-aaa3-4167-81e6-c178b00cdbf0.png">
What this image is showing is that as the cities we looked at began to get closer to the equater (closer to 0 degrees latitude) the temperatures began to rise and as the latitude got further and further away from the 0 degrees latitude both in the negative and positive direction, meaning north and south of the equater the tempatures both dropped. Like an upside down U.

In our next image below, we were looking at the humidity versus the latitude of our respective cities. This plot displayed that regardless on where the cities were lying (close to the equater, south of the equater, or north of the equator) across the board many cities experienced high humidity regardless of location.
<img width="1044" alt="Screen Shot 2022-08-27 at 4 51 26 PM" src="https://user-images.githubusercontent.com/106457512/187047566-9ca4b0cb-a95c-46ed-8467-6b819f3c3e5f.png">

Our next scatter plot showcased is the cloudiness (%) versus Latitude as shown below. Here we see the most cloudiness the further away from the equator. So we if know that the equater sits at 0 degrees latitude those cities sitting furthest north and furthest south have more cloudiness than those who were closest to the equator.
<img width="1073" alt="Screen Shot 2022-08-27 at 4 53 55 PM" src="https://user-images.githubusercontent.com/106457512/187047657-6b4b9c47-9ebe-49d4-8da6-7f34dc99cd50.png">

Finally, the image scatter plot showcased below illustrates Latitude versus Wind Speed. The wind speed across the board appeared low regardless of where on in the hemispheres the cities were situated. The plot shows that wind speed (MPH) shown began at zero and went as high as almost 40 mph. The majority of the cities were all below 15 mph regardless if they were north of the equator, near the equator or south of the equator.

<img width="996" alt="Screen Shot 2022-08-27 at 4 56 41 PM" src="https://user-images.githubusercontent.com/106457512/187047731-93e15c1c-b06b-43d1-acab-630fe24b96d0.png">

Additionally, for our WeatherPy file here are images showcasing Linear Regression:

<img width="605" alt="Screen Shot 2022-08-27 at 5 00 42 PM" src="https://user-images.githubusercontent.com/106457512/187047841-36d4036d-1aa4-4074-96cc-5cfd5e21c067.png">

<img width="622" alt="Screen Shot 2022-08-27 at 5 01 25 PM" src="https://user-images.githubusercontent.com/106457512/187047864-f4ed34c6-7600-42fa-ae63-fe7be310a63c.png">

<img width="622" alt="Screen Shot 2022-08-27 at 5 01 49 PM" src="https://user-images.githubusercontent.com/106457512/187047874-645893d5-a02a-4705-9e4d-bdf259ea87fb.png">

<img width="622" alt="Screen Shot 2022-08-27 at 5 02 10 PM" src="https://user-images.githubusercontent.com/106457512/187047884-d6edae43-3bd1-4cbc-ac62-5bfae73f37a6.png">

<img width="634" alt="Screen Shot 2022-08-27 at 5 02 55 PM" src="https://user-images.githubusercontent.com/106457512/187047904-dfdae448-60a5-4b3a-8384-aa815a7a61ef.png">

<img width="634" alt="Screen Shot 2022-08-27 at 5 03 34 PM" src="https://user-images.githubusercontent.com/106457512/187047915-dba9f2fa-fa37-4e28-b51d-c5ad491f475c.png">

<img width="634" alt="Screen Shot 2022-08-27 at 5 03 57 PM" src="https://user-images.githubusercontent.com/106457512/187047924-d5872f7c-390f-44b6-88b1-b94dd426d4a4.png">

<img width="634" alt="Screen Shot 2022-08-27 at 5 04 32 PM" src="https://user-images.githubusercontent.com/106457512/187047946-8169e541-2435-46c9-96c9-b402b2918248.png">


And then, the second requirement was to compute the linear regression for each relationship. And, separating the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).
Afterwhich, we created VacationPy to plan a future vacation in a desired destination based on weather. To complete this part of the assignment, I was tasked with creating a heat map that displays the humidity for every city from Part 1 (WeatherPy). Then I had to narrow down the DataFrame to find the ideal weather condition. For example:
A max temperature lower than 80 degrees but higher than 70
Wind speed less than 10 mph
Zero cloudiness
And then finally, drop any rows that don't satisfy all three conditions, to be sure that the weather is ideal.

The first image below shows the heatmap of the humidity across our respective cities
<img width="1132" alt="Screen Shot 2022-08-27 at 5 07 07 PM" src="https://user-images.githubusercontent.com/106457512/187048008-1c474105-c096-4d6d-9755-e81758e1150c.png">

The second image below shows the cities where the temperature was greater than 70 degrees but less than 80 degrees, the wind speed was less than 10pm, and that the cloudiness was 0; essentially meeting our "ideal" criteria in a dataframe.

<img width="932" alt="Screen Shot 2022-08-27 at 5 09 24 PM" src="https://user-images.githubusercontent.com/106457512/187048081-0e45c0d0-4ee8-49f9-b6bc-3d112713f4c8.png">

Finally, this heat map below showcases hotels where we could stay should we decide to visit our ideal cities for a vacation:
<img width="1144" alt="Screen Shot 2022-08-27 at 5 11 24 PM" src="https://user-images.githubusercontent.com/106457512/187048103-2b7315da-4d82-45c6-bbbc-0de8b02255d3.png">


