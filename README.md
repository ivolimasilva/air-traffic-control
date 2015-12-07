# AirTrafficControl
A simulator for an air-traffic controller in VDM++

## Description
Implement a simulator for an air-traffic controller. The airplanes should move in a two-dimensional grid according to a clock tick. Different airplanes have different speed limits (of course, the fastest one could go is one grid square per clock tick). Airplanes can only turn 45º, although some planes take longer to turn than others upon receiving the request. The planes enter the ATC radar through its limits, and will follow their original trajectory unless ordered otherwise. Each plane has a mission: it either wants to land (thus it needs to enter the runway in the correct direction and speed), or it wants to exit the radar through the N, S, E or W limits. There are always a few beacons (well known places) scattered across the grid. The ATC can order the airplane to: “Rotate Xº CW”, “Rotate Yº CCW”, “Speed Up to X”, “Speed Down to Y”, “Goto Beacon X”. Be aware of usual safety procedures such as minimal space around the airplane.

## References
[Wikipedia](http://en.wikipedia.org/wiki/Air_traffic_control)

[Manual Page Archive](http://man.cat-v.org/unix_8th/6/atc)

[VDM++ Manual](http://raw.github.com/overturetool/documentation/master/documentation/VDM10LangMan/VDM10_lang_man.pdf)
