<p>
  <a target="_blank" rel="noopener noreferrer" href="https://eloquent-khorana-84ad8b.netlify.app/">Click here for live demo</a>
</p>
<p align="center">
<a target="_blank" rel="noopener noreferrer" href="https://github.com/blakebdavies/portfolio-project/blob/main/images/vanilla-weather-app.png">
   <img src="https://github.com/blakebdavies/portfolio-project/blob/main/images/vanilla-weather-app.png?raw=true" width="600" style="max-width:100%";/>
</a>
   </p>                                                                                               
 <h2>Vanilla Weather App</h2>
 <p> This is a vanilla javascript project focused on simple, user-friendly, and global weather search functionality.</p>
 <h2> Reflection</h2>
 <ul>
  <li>Weather API Integration</li>
  <li>Geolocation API Integration</li>
  <li>Current Weather Display</li>
  <li>5-Day Forecast</li>
  </ul>
  <p>I learned so much by building this vanilla javascript project. My end goal of this project was to create a fully functional worldwide weather checker that allows you to search a city and see the weather in real-time as well as the 5-day forecast.</p>
<p>I divided this project in two phases. The first phase was creating the weather search by integrating the OpenWeatherMap API and returning the real-time, current weather of a chosen city, displaying the weather description, humidity, and wind speed. The main challenge of this phase was deconstructing the application into functions and understanding the possibilities of my chosen API, OpenWeatherMap.</p>
<p>The second phase was dedicated to creating the 5-day forecast by building the layout, styling the feature, and integrating a more complex api integration to include the data of the 5-day forecast. The first challenge of this section were deciding where I should you call the One Call Api because this could only be done once the coordinates of the city were established, so I had to find the fight place to get the forecast results, only after the first api call. The second challenge was building the string injected inside the html for each day of the forecast prediction. In order to do this, I had to concatenate a big string and then add each day one at a time for the forecast.</p>
<p>I am happy with the appearance and functionaly of the application, however I would improve it by adding in a temperature conversion, so that the user can choose whether they'd like to see the weather in ºC or ºF.</p>
