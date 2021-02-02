---
title: Maps & Data
intro: "Issues related to maps, search and other data"
versions: '*'
---

# Maps
### Why does OsmAnd not offer access to Google Maps?

Firstly, OsmAnd is meant to support OpenStreetMap and tries to go that path as far as possible. Secondly, there are licensing issues, so OsmAnd cannot be distributed with Google Maps data.

### Is there a way to have contour lines displayed in feet also, instead of meters?

Unfortunately not. This would require the generation of completely separate contour line data with different geometry and labels. You can obviously generate maps yourself using GDAL and OsmAndMapCreator but that requires technical environment check [Technical Documentation](/development).

### Create own maps

# Search
### Offline search by address does not show all streets
Check that you have correctly entered the required address in the search - city, street, house, etc.

### Offline search by address does not show the required address 

#### Problems with districts

**Check if there are any districts in your city**. The address may belong to them. You can check this on the OSM maps by opening the administrative boundaries of the city. All localities within the borders are districts. Districts can be of different types depending on the countries - district, suburb, village, etc.

---
**Example:** 
You found - Wolności 223 Zabrze
- Open [OSM maps](https://www.openstreetmap.org/) and write Zabrze in search.
- Select a search result starting with  **administrative boundary** 
- You will see a map with the boundaries of the selected city.
---
You can also use **Nominatim** . Enter the street with the house number without specifying the city. The search results will show the desired address belonging to another city. Enter the found name of the locality in [nominatim](https://nominatim.openstreetmap.org/ui/search.html), and its type will be indicated in the Address Rank line.

---
**Example:** 
You found - Wolności 223 Zabrze
- You will see Wolności Maciejów in the search results.
- Open [nominatim](https://nominatim.openstreetmap.org/ui/search.html) and write Maciejów in search.
- Select a search result with  **administrative** 
- You will see 20 (suburb / hamlet) in the Address Rank line.

>Be careful when choosing a locality in the search results.
>There may be duplicates or similar cities in other regions and countries.

# Points of Interest

# Tracks and Points
### How to mark different places on the map
*It looks like duplicated content for Personal Data category*
You can leave notes for future usage in several forms:

-   [Favorites](https://osmand.net/features/favourites): they are constant points on the map. You can add a description to every Favorite. To add it, please make a long tap -> tap Add.
-   [Markers](https://osmand.net/features/map-markers): the temporary points with the directions settings. You can see the distance from the selected point or your current location to the Marker and remove it fast. To add it, please make a long tap -> tap Marker.
-   [Waypoints](https://osmand.net/features/map-markers#markers_favorites_A): the points along your route. You can add a description to this point. To add a waypoint, please make a long tap on the map -> Directions -> rst intermediate waypoint.
-   [Audio/Video notes](https://osmand.net/features/audio-video-notes-plugin): these are points with your audio-, video-, and photo files added to the selected point on the map. Please enable the Audio/video notes plugin in OsmAnd menu -> Plugins. To add it, please make a long tap -> Actions -> select the required file to add.
-   [OSM Notes](https://www.facebook.com/watch/?v=673312246195291): your reports on the mistakes in the OpenStreetMap source. Please enable the OSM editing plugin in OsmAnd menu -> Plugins. To add it, please make a long tap -> Actions -> Add OSM note.
-   [POIs](https://osmand.net/features/find-something-on-map#Find_Points_of_Interest_A): these are the points of interest from the OSM map source. Please enable the POI overlay in Configure map menu or select a certain category in the
-   [Search](https://osmand.net/features/find-something-on-map#Find_Points_of_Interest_A).