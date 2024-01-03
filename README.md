# python-api-challenge
Final

My final Notebook Codes are saved as WeatherPy-1 and VacationPy-1 in the WeatherPy directory.

Requirements for "Part 1: WeatherPy"  
- Per the challenge requirements, I used OpenWeatherMaps API and citypy to generate a list of cities with latitude range form -90 to 90 and longitude of -180 to 180.
    - the latitude range represented 0 as the equator and -90 representing cities in southern hemisphere.  0 to 90 represents cities in Northern hemisphere.  The longitude form -180 to 180 represents cities on multiple continents.
    - Interestingly when I ran my code, each time the number of cities varied a little from upper 500's to lower 600's.  This doesn't make logical sense to me as I would have expected the city locations to be fixed.
-Per the requirements, I then created scatter plots to showcase the relationships between:
    - Latitude vs. Temperature
    - Latitude vs. Humidity¶
    - Latitude vs. Cloudiness
    - Latitude vs. WindSpeed
- The scatter plots really only showed a relationship between Latitude and Temperature with temperature declining the farther away from the equator as suspected.  The plot showed a reversal of slope at latitude = 0 (the equator)

Requirement 2: Compute Seperate Linear Regression for Each of Relationships for the Northern Hemisphere and Southern hemisphere. Below are my observations of the plots with linear regression lines:

Temperature vs. Latitude Linear Regression Plot

The Northern Hemisphere plot for temperature vs. latitude Regression Plot shows a very strong negative linear relationship between Temperature and Latitude. The R-Value being negative 0.86 is suggests it is very linear. The slope being positive means the farther you get from the equater, the colder it gets.

The Southern Hemisphere plot for temperature vs. latitude Regression Plot shows a strong positive linear relationship between Temperature and Latitude. The R-Value being positive 0.63 is suggests it is very linear, but not as strong as the Northern hemisphere. The slope being positive also suggests the farther you get from the equater, the colder it gets. I would have thought the Northern and Southern Hemispheres were very similar with R-values very similar. Possibly, the time of the year makes a difference. The Northern atmoshere is winter season right now, while the Southern atmosphere is Summer season.

Humidity vs. Latitude Linear Regression Plot

The Northern Hemisphere plot for Humidity vs. latitude Regression Plot shows a positive linear relationship between Humidity and Latitude. The R-Value being positive 0.48 is suggests it is not a strong linear relationship, but the slope does indicate the humidity does increase the farther away from the equater you get.

The Southern Hemisphere plot for Humidity vs. latitude Regression Plot shows a positive linear relationship between Temperature and Latitude. The R-Value being positive 0.19 is suggests it is not a strong linear relationship. Again the difference between Northern and Southern may be, because of the seasons.

Cloudiness vs. Latitude Linear Regression Plot

The Northern Hemisphere plot for Cloudiness vs. latitude Regression Plot shows a positive linear relationship between Humidity and Latitude. The R-Value being positive 0.39 is suggests it is not a strong linear relationship, but the slope does indicate the humidity does increase the farther away from the equater you get.

The Southern Hemisphere plot for Cloudiness vs. latitude Regression Plot shows a positive linear relationship between Cloudiness and Latitude. The closer you get to the equater, the clouder it gets. The R-Value being positive 0.23 is suggests it is not a strong linear relationship. Again the difference between Northern and Southern may be, because of the seasons.

Wind Speed vs. Latitude Linear Regression Plot

The wind speed does not appear to be related to the Latitude in the Northern Hemisphere. The very low R-value of .026 suggest there is no linear relationship.

The wind speed does suggest some negative linear relationship related to Latitude, however with a R-value of -.32, it does not appear to be a strong linear relationship. Again, I think the difference between North and South Hemispheres may be related to the season.

Conclusion: 

The temperature seems to have the greatest linear relationship with distance from the equater. The farther you get from the equater, the colder it gets. Only based on distance from equater, I would have thought Northern and Southern were very close. This leads me to believe another factor is involved. I think it is related to the tilt of the earth in relationship to the sun. To get a better comparison, it maybe necessary to sample data year around or at least during the 4 seasons of the year for Northern and Southern hemispheres.


Requirements of "Part 2: VacationPy" I really struggled with my Jupyter Notebook working properly.  Initially completed all of the requirements before New Years, except for writing the final conclusion and readme file.  When I came back to complete, I ran each portion of the code again from top to bottom.  As I ran the code again, it had errors with each run.  I don't understand why it worked really good before New Years and now it doesn't.  Anyways, after hours of debugging, I got everything to work.  However, I don't believe it looks as good as before.  The following tasks are working and completed:

- Map displaying every city in the city_data_df dataframe
- Cities narrowed down to ideal weather conditions.
- Hotels within 10,000 meters of city with ideal weather conditions.
- Hover message working correctly for each idea location.

I utilized ChatGPT to help me identify proper imports to accomplish the challenge.  i also utilized ChatGPT to help me write and debug the code in completing the challenge.  The AskBCS learning assistant was not available over holiday break so I was not able to utilize there assistance.