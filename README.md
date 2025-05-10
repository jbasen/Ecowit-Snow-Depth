# Ecowit-Snow-Depth
Uses the Ecowitt LDS01 laser distance sensor and Ecowitt GW1200 gateway 
to measure snow depth and provides a trigger thatn can be routed to a
notification module of your choice as a reminder of when to clear your
driveway/walkway of snow before it gets too deep.  The trigger fires
each time a user defined depth of snow has accumulated.  

The code also requires input of current conditions (snow, rain, wintery-mix,
sun, etc.) and the baometric pressure trend (rising, falling, steady) as
strings.  A module is included to obtain these from a WeatherFlow Tempest
Smart Weather System station.  However, they could be sourced from another
source including the Internet.  However, if these strings are different
than those provided by the WeatherFlow module, then the Ecowitt Snow Depth
S+ module may need to be changed.

v1 - Initial Release
