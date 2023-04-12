# LED-clock
Firmware for a clock made with ESP8266 board and 8x32 LED matrix

Features:
- wi-fi connectivity
- weather info from OpenWeatherMaps
- 3 sizes of clock display
- weather animation in background
- temperature display
- brightness setting from encoder

TODO and known bugs:
- ESP8266 resets randomly every couple of days with HW WDT reset
- button not doing anything
- settings (display and brightness) are not saved after restart


WDT reset log to deal with later:
```
ets jan 8 2013, rst cause:4, boot mode: (3,6)

wdt reset
load 0x4010f000, len 3424, room 16
tail 0
chksum 0x2e
load 0x3fff20b8, len 40, room 8
tail 0
chksum 0x2b
csum 0x2b
v0004d1e0
~ld
```
