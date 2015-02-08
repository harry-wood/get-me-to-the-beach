# Get me to the beach

Get me to the beach is a one button app (website) which gets you to the beach.

**[Try out 'Get me to the beach' here](http://harrywood.co.uk/get-me-to-the-beach)**
 
Click 'go' and it will detect your location and tell you how to travel to the nearest bit of beach using [TransportAPI's public transport journey planning API](https://developer.transportapi.com/documentation/public-journey-planning) or [cycle planning](https://developer.transportapi.com/documentation/private-journey-planning)

## Hack Bournemouth ##

This was a one day hack developed for an event called '[Hack Bournemouth](http://hackbmth.org)' 

## How it works ##

The site is just javascript and HTML using...
* [TransportAPI's public transport journey planning API](https://developer.transportapi.com/documentation/public-journey-planning) in 'region=southeast' mode (using Traveline Southeast at the back end)
* [TransportAPI's cycle planning](https://developer.transportapi.com/documentation/private-journey-planning) which is wrappig that of [Cyclestreets](http://www.cyclestreets.net)
* Open licensed ODbL maps from [OpenStreteMap.org](http://openstreetmap.org)
* Tiles from the 'standard' OpenStreetMap tile server CC-BY-SA ([usage policy](http://wiki.openstreetmap.org/wiki/Tile_usage_policy))
* Map presentation javascript library is [LeafletJS](http://leafletjs.com)
* [jQuery](http://jquery.com) for ajax and DOM.
* [A photo of Bournemouth Beach by Christophe Finot](http://commons.wikimedia.org/wiki/Bournemouth#mediaviewer/File:Bournemouth_06.JPG) CC-BY-SA.2.5, found on wikimedia commons
