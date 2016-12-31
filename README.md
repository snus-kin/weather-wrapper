# weather-wrapper
A bash wrapper for wttr.in.

# Usage
A bash wrapper for wttr.in.
Displays weather forecast for a location, or the current phase of the moon.
Options:
  -0, --today:     Display today's quadripartite weather forecast
  -1, --tomorrow:  Display tomorrow's
  -2, --nextday:   Display the next day's
<<<<<<< HEAD
  -3, --three:     Three-day quad
=======
  -3, --3day:      Three-day quad
>>>>>>> 7f25647b3ebb3a4a787d5275bff1ad6eae69df16
  -c, --city CITY: Specify the location city as CITY, e.g. -c Berlin
  -m, --moon:      Show the moon phase (location agnostic)
Without any options, display today's simple forecast for your default location

# TODO
- [ ] read defaults from config file including default city
- [ ] make only one curl request when combining -0, -1, -2
- [ ] weather and moon should probably be permitted together, outputs concatenated
