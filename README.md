# WEATHER APP

## Description

Third-party APIs allow developers to access their data and functionality by making requests with specific parameters to a URL. In this weather application you will be able to search your city to see the 5 Day Weather Forcast. Along with the current weather for that current day. 

## Installation

Create a directory for the entire application, then add appropriate folders and files.
Create an APIKey from the OpenWeather webpage that provides APIs. 
Make sure to append the APIKey to the geocode API URL to call and receive a response with longitude and latitude data from a given location. Retrieve another URL to pull the forecast data. 
Then create variables for the longitude and latitude values and place them into the forecast API call URL to pull weather data for user input city. 
Create a loop that will run through data needed in place of the slots created to display weather information. 
A local storage was used to store inputted data to retrieve in the side column. 
Then you will be able to input a city and pull data from OpenWeather API! 
Bootstrap was used for CSS styling.

## Usage

Upon opening application, there will be no data but placeholders for where the user should expect information. User is able to input a city and hit enter, or click search which then will pull weather data, including cloudy/sunny icon, temperature in Farenheit, wind gust, and humidity. It will also display the next 5 days with the same expected data. Searched cities will show up as button under the search bar in which user is able to pull back weather from previously searched. Each city searched will append at the bottom of each button.

Opening application page:
![alt text](./images/Screenshot%202023-06-09%20at%208.34.29%20PM.png)

Example city:
![alt text](./images/Screenshot%202023-06-09%20at%208.35.05%20PM.png)

Link to use application: 

## Credits

The TA's provided much needed help with this application. 

OpenWeather API site: https://openweathermap.org/forecast5

Bootstrap: https://getbootstrap.com/docs/5.1/getting-started/introduction/
