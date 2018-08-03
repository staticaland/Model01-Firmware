# Keyboardio Model 01 Firmware

This is a very early version of my custom Keyboardio Model 01 firmware.

I use [Kaleidoscope-Docker](https://github.com/keyboardio/Kaleidoscope-Docker) to build the firmware:

```
bin/builder -s https://github.com/staticaland/Model01-Firmware.git \
	-p https://github.com/keyboardio/Kaleidoscope-SpaceCadet \
	-p https://github.com/keyboardio/Kaleidoscope-Unicode \
	-p https://github.com/keyboardio/Kaleidoscope-HostOS
```
