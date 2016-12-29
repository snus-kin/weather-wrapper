# weather-wrapper
A bash wrapper for wttr.in

# Usage
`./weather (-c, -h, -3) (--city, --help, --3-day)`  
-c, --city: specifies city to be given to wttr.in, without wittr.in predicts  
-h, --help: display help text  
-3, --3-day: display full 3-day forecast  
-m, --moon: display the moon forecast for the current day  
Running just `./weather` will give a predicted location, current forecast (the output of curl wttr.in | head -7)
