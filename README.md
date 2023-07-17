# python-api-challenge
This repo uses a Python requests, APIs, and JSON traversals to look at weather for specified locations in relation to distance from the equator. Weather data for this analysis came from the OpenWeatherMat API and location data was retrieved through the Geoapify API. This activity is broken down into two deliverables, WeatherPy and VacationPy. Both the ***WeatherPy.ipynb*** and ***VacationPy.ipynb*** Jupyter notebook files are located in the **WeatherPy** folder.

## Part 1: WeatherPy
Part 1 uses Python script to visualize the weather of over 500 cities of varying distances from the equator. The citipy Python library and the OpenWeatherMap API are used to create a representative model of weather across cities. Part of the excercise involves creating plots to showcase the relationship between weather variables and latitude and then saving the figures as a png file. Those files can be found in the **WeatherPy/output_data** subfolder. We also export a list of the cities to csv for use in Part 2. That csv file is also located in the output_data subfolder.

## Part 2: VacationPy
Part 2 uses the csv file from Part 1, the geoViews Python library, and the Geoapify API to plan future vacations based on specific criteria. The results of that analysis are presented through map visualizations.
