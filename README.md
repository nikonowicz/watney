Watney Rover
------------

[Sample Video](https://i.imgur.com/ZHjlQ2Y.gifv)

Watney is a low-cost Raspberry Pi-enabled rover made of readily available parts. At the heart of it is
Raspberry Pi Zero W powered by a small phone battery bank. Two geared DC motors and an H-bridge controller
provide direct drive to rear wheels and an RPi camera is mounted in the front.
Very little to no soldering required.


Besides the components listed above, some breadboard jumper wires and M3
screws, the rest of the components are 3D-printable.

The software part of Watney is written in Python and provides webcam-on-wheels
functionality. The camera feed is low-latency 720p and you control the rover from the browser.


Ingredients
------------


* Raspberry Pi Zero W
* 40 pin header (either regular or solderless)
* Raspberry Pi Camera V2
* RPi Zero-compatible camera ribbon cable
* USB power bank that provides at least 800ma
* 2x Arduino geared DC motors
* L298N H-bridge controller
* 12x 10cm Female-to-female jumper wires
* M3 screws