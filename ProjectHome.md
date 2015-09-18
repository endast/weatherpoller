This program is designed to interface with the [FineOffset](http://www.foshk.com/) line of weather stations (WH1080, WH1081, W-8681, etc). These are also sold under other brands, such as Proove WP1400, the model I have.

The information about how the data is stored on the device is based on information from Jim Easterbrooks [webpage](http://www.jim-easterbrook.me.uk/weather/mm/), including the [EasyWeather.dat layout](http://www.jim-easterbrook.me.uk/weather/ew/).

It was developed as a commandline alternative to the Windows program [EasyWeather](http://proweatherstation.com/easyweather/easyweather.htm).

To write this program, the [USB Protocol](http://code.google.com/p/weatherpoller/wiki/USBProtocol) used was sniffed using [SnoopyPro](http://sourceforge.net/projects/usbsnoop/).

**Note**: I don't use this program actively myself anymore, since I found this more complete project which does a lot more things across the board http://jim-easterbrook.github.io/pywws/doc/en/html/index.html and is highly recommended. (Not if you want a minimalistic C version of course).