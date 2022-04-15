## Overview
### Purpose 

Vacationing, although mostly for pleasure and creating memories of a lifetime, can be stressful to plan. Agencies have been specifically created to ease the confusion and indecisiveness of locations, travel routes, and overall itineraries. The knowledge that agencies have are mostly gained through data scraping and the use of application programming interfaces. With a general list of preferences and desired trip activities, a data analyst could provide a comprehensive list of 5-star restaurants located within 50-mile radius of an Airbnb that’s located in a city with a temperature range of 65-80°F and low humidity. The following examples will show various ways that data such as weather information, hotel locations, and travel routes can be collected and presented to eager travelers.

### Weather Analysis and Trip Itinerary

Some travelers may be the risk-taking type and put the location of their adventure in our hands with only a few preferences.  In the following example, we were able to create ~2,000 random longitude and latitude points, and with the aid of Citypy find the closest city to these points. Through the OpenWeatherMap API system we were then able to find various information on all cities we have generated such as temperatures, humidity, winds, general description of weather, etc. The following graphs are visualizations of certain data we were able to gather based on latitude and various weather aspects.

![Fig1](https://user-images.githubusercontent.com/100329223/163509978-232fbd9a-8b0f-4800-9f2b-4edf38cdc834.png)
![Fig2](https://user-images.githubusercontent.com/100329223/163509990-fd70e1b4-1f47-48a8-9890-0d980a29c4b7.png)
![Fig3](https://user-images.githubusercontent.com/100329223/163509998-2d3bb7f6-c601-480f-88a3-b16445e8e205.png)
![Fig4](https://user-images.githubusercontent.com/100329223/163510007-d4ffedc0-c6c4-4cc7-b234-ea2e82f1ebdc.png)

There are also may map types that we can display our findings. Below is a visualization of the maximum temperatures for the lodges in cities we randomly picked. This is considered a heat map and the warmer cities are given a red color, while the cooler cities are green.

![heat_map](https://user-images.githubusercontent.com/100329223/163510047-91570b5b-5745-484f-a3c9-4e7d637f5116.png)

With the aid of GoogleMaps API we were able to find lodging within a given distance from the generated cities. Below is a map that displays these lodges through markers and shows a select few items in regards to the location, when clicked on.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/100329223/163510093-274f9e55-b79b-4ebb-9a46-c9e96b09e736.png)

Once we are able to narrow our search we can provide customers with a map that shows travel routes and information boxes on the stops along the way.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/100329223/163510173-f8354e0e-e3ce-4afc-a2a8-c32cb694754f.png)
![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/100329223/163510201-204ee98c-d3a3-4934-bcf7-6e0d42bf6f70.png)

Upon the return of the trip, the customers rave about their experience and how all the requests they made were met, and then some. Ultimately, the power of finding the right data, modifying the outcomes, and presenting a final project that meets the needs of a client, can be exhilarating for all parties.
