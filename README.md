# UFO Sightings with JavaScript
Use JavaScript, HTML, and CSS to create a custom webpage that showcases different UFO sightings around the world. 

## Project Overview 
Although Dana's website and dynamic table were functioning as intended, she wanted to offer a more thorough analysis of UFO sightings by enabling viewers to simultaneously select for several parameters. In this project table filters for the city, state, country, and shape were added in addition to the date. The app.js file's handleClick() function was updated using JavaScript to a new function that records the element, value, and id of the modified filter. The dataset was then looped through using a new function, which only kept the results that fit the search criterion.

## Results 
### **The Truth Is Out There!**
<img width="1440" alt="webpage" src="https://user-images.githubusercontent.com/105958160/186284862-6d1ef70b-1210-4624-90fe-f65274e8ffaa.png">

As you can see, the table filters by Date, City, State, Country, and Shape are now located under the "Filter Search" section.

<img width="195" alt="FilterSearch" src="https://user-images.githubusercontent.com/105958160/186296574-56228516-7c48-4ae7-8bb8-ecef540ad997.png">

The table on the right will refresh to display the results as soon as you enter the search criteria in the filters.

<img width="1426" alt="FilteredExample" src="https://user-images.githubusercontent.com/105958160/186301184-5e73d130-e8e0-4ebe-b505-1777fc05bda8.png">

## Summary
The website has a few drawbacks, one of which is that the filters are case-sensitive. Only lowercase search terms are permitted; otherwise, your search will not return any results. Less restrictive case sentivity would make it easier for consumers to search.

Another might be that the data appears to be out of date and is not updated in light of fresh information. Add the ability to retrieve data from a live source that contains both current and historical data.

After entering the information in the filter fields, there is no button for the user to click in the "Filter Search" section. They must be aware of the enter key in this case. You would have to remove the currently used filters before beginning a new search. For a simpler search, an option to clear the filters and a button to search the filters should be included.
