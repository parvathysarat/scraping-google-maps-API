# Scraping of location and details using Google Maps API
## Safe Spots
Safe Spots are essentially buildings or locations that can be considered safe in a locality. This exercise was undertaken as a part of Safecity initiative to aggregate details of spots that one can depend on for safety in times of a perceived threat or danger. We have considered public places such as police stations, and spots where crowds maybe present such as malls, as they relatively safe. The spots were to be collected and embedded onto Safecity maps, as a quick resource that can be depended upon.

The locations of the following safe spots were gathered for various cities :

1. Police Stations
2. Hospitals
3. Malls

<b> Code here demonstrates flow for collecting details of Delhi hospitals. You'll need to obtain an API key from https://developers.google.com/places/web-service/intro. </b>

## Google Maps API
Google Maps API allows the user possessing a relevant API key to scrape locations and their details from Google Maps. There are various API's available; <b> Places API </b> is specifically for the places' details.

The API allows search to be scripted both by -

1. Specifying location name
2. Specifying location co-ordinates (latitude, longitude) as well as radius from the location within which the spots need be to located

The corresponding <b> format for the above url queries can be found at https://developers.google.com/places/web-service/search. </b>

NOTE: Only first 60 search results can be scraped for free.
