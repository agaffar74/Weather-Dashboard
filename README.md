# Weather Dashboard
## Description
This applicaiton is a weather dashboard that will run in the browser and feature dynamically updated HTML and CSS with search functionality to find current weather conditions and the future weather outlook for multiple cities. 

## User Story
AS A traveler
I WANT to see the weather outlook for multiple cities
SO THAT I can plan a trip accordingly

## User Experience
This application utilizes the AJAX to hook into OpenWeather API to retrieve data in JSON format. Using dynamically updated HTML and CSS powered by jQuery we can show the user the follwoing information: Displayed the following under current weather conditions:

City
Date
Icon image (visual representation of weather conditions)
Temperature
Humidity
Wind speed
UV index Include a 5-Day Forecast below the current weather conditions. Each day for the 5-Day Forecast should display the following:
Date
Icon image (visual representation of weather conditions)
Temperature
Humidity
It also Includes a search history so that users can access their past search terms. Clicking on the city name that populates under the search bar after their initial search, will perform a new search that returns current and future conditions for

Site Demo
site

## Technologies Used
jQuery - Used for event listeners of parent and childeren elements as well as to store and recall those varible in local storage to be displayed dynamically in HTML on the page.
momentjs - Used to pull current date for the current city.
javascript - Used to dynamically change html and store user-input.
Bootstrap - Used to pull existing html and CSS for creating resposive organizational structer and styling for the site.
HTML - Used to create elements on the DOM
CSS - Styles html elements on page
Git - Version control system to track changes to source code
GitHub - Hosts repository that can be deployed to GitHub Pages
Code Snippet
Pulling from the Openweather API listed bellow are the two calls within the city search function. These two calls are run when our onclick is triggered in our event listener. Onced this function is told to run it pulls the necessary information from the object retreived from the queryURL and we parse out the information we need into new varible elements we create. Taking these new elemetns we then append them into a new div that gets inserted into the HTML tag that we cleared at the begining of our function.

## Built With
API
jQuery
HTML
CSS
Boostrap
Authors
Chris Melby

LinkedIn
Link to Github
Portfolio# Weather-Dashboard