# World_Weather_Analysis

## Purpose

In this endeavor, we are grabbing some weather data from a set of randomly generated coordinates. We can look at the weather in areas at a glance, and utilize this data to create a basic search functions for people looking for a nice place to go on vacation!

Since we are doing that, we will also grab local hotels, and show how we can utilize this data to plan trips if that was something we wanted to include for end-user functionality.

## A Peek Inside

Let's take a look at the result from grabbing this data by looking at what the gmaps library produces with the help of Google Cloud's API.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/95941301/152491148-31726854-d31f-4f96-9080-6c7efa2b9f09.png)

Here, we have some information on a map. The heat markers show the general area where the affected weather is, and the marker will give you more details on what that weather is exactly.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/95941301/152491306-5555ed89-680f-4a1f-96d3-81a962ba3a48.png)

If we wanted to, we could possibly implement something so the end-user can create a trip plan without having to use a seperate window and refer back to the data.

And below is that same result, with only markers and no road maps.

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/95941301/152491451-3ad4e125-d60b-4e1f-84ed-85f9409e0bbc.png)
