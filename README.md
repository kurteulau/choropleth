# Choropleth Map

![alt text](choropleth-static-image.png 'Static map image')

### What's a choropleth map and how do you make one?
A [choropleth map](https://en.wikipedia.org/wiki/Choropleth_map) is a map in which areas such as countries, states, or other geographic areas are colored in proportion to a particular measurement. In this case, the map was created using the US population density in terms of number of people per square mile in each state, based on the tutorial found at [Mapbox](https://www.mapbox.com/). 

### So what?
The purpose of this map is to make state-level population patterns easier to visualize, as compared to the same data presented in a spreadsheet. You can observe that the highest density states reside in New England and the Mid-Atlantic, with Florida and California also illustrating denser populations.


### Notes
I've made alterations from the form prescribed tutorial with the hope that the viewer will better understand the embedded data. I've also factored out all custom styles into stylesheet.css to make index.html more concise.

You can check out the tutorial here:
* [Tutorial Part 1](https://docs.mapbox.com/help/tutorials/choropleth-studio-gl-pt-1/)
* [Tutorial Part 2](https://docs.mapbox.com/help/tutorials/choropleth-studio-gl-pt-2/)

As noted in the links above, shout out to [Leaflet](https://leafletjs.com/examples/choropleth/) for curating the data.

Next step when have time: include data from most recent census since data used in this project is from 2011.