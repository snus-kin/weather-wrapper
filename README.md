# weather-wrapper
A bash wrapper for wttr.in.

# Usage
Displays weather forecast for a location, or the current phase of the moon.  
Options:  
  -3, --3day:      Get the full, 3-day forecast  
  -c, --city CITY: Specify the location city as CITY, e.g. -c Berlin  
  -m, --moon:      Show the moon phase (location agnostic)  
Without any options, it will return a 1 day forecast for your current location

# TODO
- [ ] Add some way of making a 'default' city that isn't guessed by wttr.in  
- [ ] Add more specific commands (-t for tomorrow?)
  
