# US-Counties-lat-lng
A JSON file with US counties grouped by state and their geographic center coordinates.

The JSON has this structure:

```{
  "STATE_ABBREVIATION":
  // County Array
  [
    // County Object 
    {
      "name": "COUNTY_NAME", 
      "lat": "LATITUDE_COORDINATE",
      "lng": "LONGITUDE_COORDINATE"
    },
    ...
  ],
  ...
}```

The data is pulled from this wikipedia page: https://en.wikipedia.org/wiki/User:Michael_J/County_table#cite_note-kingsalmon-5
