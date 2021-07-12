# mobiWeather assignment
===================


Integration with [Open Weather Data API](https://openweathermap.org/api) in order to show current and forecast weather data of 5 european cities.
Open Weather Data API
To complete the proposed exercise two different kinds of APIs are needed.
For example, to get the current weather data in London:
http://api.openweathermap.org/data/2.5/weather?q=London,uk&appid=3d8b309701a13f65b6
60fa2c64cdc517
More details here http://openweathermap.org/current
It is possible to find more information here http://openweathermap.org/api
----------


Usage
-------------

Clone the repository

    git clone https://github.com/vasanthabharath/mobi.git

Install dependencies using [npm](https://www.npmjs.com/)

    npm install
Run the App

    npm start

Run unit tests

    npm test

Run end-2-end tests

    ng e2e
    


Technologies
-------------

 - Angular 4.0
 - TypeScript 2.3
 - Angular-CLI 1.2.7
 - Bootstrap 4.0.0-alpha.6
 - Chart.js 2.6

About the project
-------------

 - Single page App separated in 3 main Components: City selector, City's forecast (5 days) and City's forecast chart.
 - Using [owfont](https://websygen.github.io/owfont/) for displaying weather icons.
 - Using [Chart.js](http://www.chartjs.org/) for the chart that displays Temperature, Humidity and Wind speed for the selected city.
 - Changes forecast data and chart's data when selecting a new city.

Future implementations or improvements
-------------
Exercise
Please use Open Weather Data to create a single page application that has 2 sub-pages.
1. Home/landing page: It should display a list of 5 European cities (you can choose the
ones you prefer). Each city should display the city name, temperature, sunrise time
and sunset time. Clicking on this tile should open another sub-page as explained in
point #2 below. (Use routing)
2. For a clicked city, it should display temperature and sea level for the next 5 days at
9:00....>I will update this in future
Achieve responsive design. (You can use bootstrap or any UI library). We would prefer if you
will deliver the code using BitBucket (private repo) but also a zip file is fine.
Open Weather Data API   ---->need to write mediaquries


