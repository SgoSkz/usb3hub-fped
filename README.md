# usb3hub-fped USB 3 Hub for Programmers &amp; Embedded Developers

## What's wrong with normal USB hubs? **Nothing**. USB hubs have tons of
features like an SD reader, HDMI/DP output (video), EXTRA USB PORTS (shocking),
and sometimes even audio jacks. These are all great features, _but_ I want a
USB hub that has features for embedded programming such as i2c, spi, uart, and
maybe even jtag (prob not). Mainly because I'm tired of having 4 different
devices for dealing with one project.

## Goals
- [ ] Basic USB hub functional
- [ ] SD card reader
- [ ] Embedded programmer stuff functional

## Plan
- 3x USB 3 downstream ports available
- 1x USB 3 downstream reserved for USB 2 hub
- USB 2 hub connects to embedded programming devices and SD reader

## Hardware
- Utilizes the TUSB8041
- Embedded stuff
	- Possibly put an ATmega32u4
		- Easy to program with native USB support
	- Individual IC's for i2c, spi, uart, etc
	- Other IC/uC
- Power management ICs
	- 1v1	->
	- 3v3	->
	- 5v	->
- XTAL selection
	- 24MHz	->

## Software
- Developed in KiCAD :D

## License Here When Chosen
- Ermmm =T
