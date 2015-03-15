This Project was started by Dennis Frie

The main purpose of this project was to make a DIY OSD that can be made with;

> Opensource software
> Simple and cheap hardware
> Only little technical knowledge required


It's not intended to be a graphic-heavy OSD, but an easy readable OSD with the most important info. But it's opensource and you can do whatever you want with it.

Quite a few updates and features have been added by request from users - and I hope to continue this. Feel free to post suggestions - but be reasonable. I don't mind to implement a feature - but I'm not gonna rewrite it all for another purpose etc.

I decided to make this project freely available and opensource - and I don't plan to earn anything on my work. Neither do I intend to sell or produce anything - but others are welcome to use it as they want.

If you don't want to make the hardware yourself the software also supports SimpleOSD OPEN (16 mhz with arduino bootloader and LM1881 sync seperator). It's should be available from here:
http://flytron.com/osd-headtrackers/...uino-boot.html

The OSD support theses features at the moment:

> Easy hardware design with Arduino
> Easy setup section added to code
> Speed from GPS
> Altitude from GPS
> Flight timer from GPS
> Position from GPS
> Heading from GPS
> Current from current sensor
> mAh used
> Auto set home position
> Calculate Line of sight
> dimming of text background
> Arrow pointing home
> Speed in km/h
> Flight summary (max altitude, max speed, max LOS, total distance traveled and average speed)
> Support NTSC and PAL
> Support SimpleOSD open 16 mhz version with arduino bootloader