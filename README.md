## USB-C Seven Seg
A USB-C controlled seven segment display, to try out some really tiny SMD 7 seg displays

Designed to be assembled by JLCPCB, using basic parts where possible

Uses a WCH [CH32V203 micro](https://github.com/openwch/ch32v20x) as its small, cheap, has USB 

Credit to Adafruit for the idea of hiding the programming pads on the other side of the USB-C connector

### TODO
- Work out why JLCPCB assembly is so pricy. Maybe this needs to be single sided?
- Check footprint for USB-C connector
- Maybe tidy up the routing, its quite vibe/push-n-shove currently
- Order Rev1 and bring up
- Think of firmware API. USB-CDC, `2.0 <enter>` seems good for now
- Write the firmware
