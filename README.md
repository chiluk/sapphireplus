# sapphireplus
Here are my Klipper configs for making the Sapphire Plus v1.1 with 3xtmc2208 + 2 x tmc2225 + belted dual z steppers.

My bltouch is connected to my ZMax, adjust pinouts if yours is connected to ZMin.  All of my endstops are currently connected.
My printer is connected to my pi via USB.

Configs for a functional 3dtouch are currently commented out, but you could use those if you have that.

$ cp 98-sapphire.rules /etc/udev/rules.d/ \
$ cp -r klipper_config ~/klipper_config

Don't forget to go through initial setup and configurations on Klipper's website to make sure.

My printer is currently not working because of hotend and extruder hardware problems, but the config should work once I get it the hardware figured out.
