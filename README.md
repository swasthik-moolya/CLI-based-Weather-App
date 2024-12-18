# CLI weather app using weather API

<p> a CLI weather app in Python that fetches and displays current weather data for a user-specified location (e.g., Bengaluru, IN) using a weather API. Show basic information such as temperature, humidity, and weather conditions.

>Understanding the Requirements:

-API Integration: We'll use OpenWeatherMap in this task. We'll need to sign up for an API key.<br>
-User Input: We'll prompt the user for a city name followed by comma and first two letter of the Country.<br>
-Data Fetching: We'll make an API request to fetch weather data.<br>
-Data Parsing: We'll extract relevant information from the JSON response.<br>
-Output Formatting: We'll display the weather information in a user-friendly format.<br>

>Code Explanation:

-Import necessary libraries: requests for making API requests and json for parsing JSON data.<br>
--get_weather function:Takes a city name as input.<br>
-Constructs the API URL using the city name and API key.<br>
--Makes a GET request to the API.<br>
-Parses the JSON response and returns the data.<br>
--Includes error handling for potential exceptions.<br>
-display_weather function:Takes weather data as input.<br>
--Extracts temperature, humidity, and weather description from the data.<br>
-Prints the extracted information in a formatted way.<br>
--main function:Prompts the user for a city name.<br>
--Calls get_weather to fetch data.<br>
--Calls display_weather to display the results.</p>
