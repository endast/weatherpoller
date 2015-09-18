# Introduction #

This information is based on the information found on Jim Easterbrook's [webpage](http://www.jim-easterbrook.me.uk/weather/mm/), which contains more detailed information.

# Layout #

There is 65535 bytes of memory available on the weather display.

The first 256 bytes of these is a fixed block that is used for settings and other global data.

The rest of the memory is layed out in 4080 16 byte chunks containing the weather history.
