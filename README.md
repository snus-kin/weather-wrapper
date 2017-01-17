# weather-wrapper
A bash wrapper for wttr.in.

# Usage
A bash wrapper for wttr.in.  
Displays weather forecast for a location, or the current phase of the moon.  
Options:  
  -0, --today:     Display today's quadripartite weather forecast  
  -1, --tomorrow:  Display tomorrow's  
  -2, --nextday:   Display the next day's  
  -3, --three:     Three-day quad  
  -c, --city CITY: Specify the location city as CITY, e.g. -c Berlin  
  -m, --moon:      Show the moon phase (location agnostic)  
Without any options, display today's simple forecast for your default location  

# Why a Wrapper?
Firstly, if you're looking for a self-hosted all singing all dancing program that does this: <https://github.com/schachmat/wego> is a good option, however it requires go and an api key, this program is more portable, only requiring curl.
(for moon phase output use <https://github.com/chubin/pyphoon>)

Also, before this I had never programmed anything in bash so it was a bit of a challenge.

# TODO
- [x] read defaults from config file including default city
  - [ ] expand to work with more options  
- [x] make only one curl request when combining -0, -1, -2
- [ ] weather and moon should probably be permitted together, outputs concatenated
