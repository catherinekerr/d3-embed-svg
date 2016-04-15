Embedding SVG Maps in D3
========================
This example uses a map that was created in Adobe Illustrator and exported as an SVG file. Although it might be preferable to use GeoJSON files for geographical maps, they are not always available in the detail that is required. In any case, we could be using any irregular shaped SVG graphic created by an application like Illustrator - this example shows how to embed the SVG into D3 and bind data to the paths.

The SVG file is quite simple. Each county is identified by a path and an id. Some paths are grouped together to denote Northern Ireland and the Republic. The path titles are dynamically created in the program. 

The data in this case comes from the [Irish Central Statistics Office](http://cso.ie/) and gives the average rental prices for houses/apartments in each county in the Republic of Ireland in 2015. The map is a chloropleth using a quantize scale. Another useful feature of this example is the zoom and center feature which centers the county's bounding box in the map container.

Hover over a county to display the county name and average rental. Click on a county in the map or in the table to zoom in to that county. Click on a legend box to highlight all counties in that range.

