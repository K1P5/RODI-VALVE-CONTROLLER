# RODI-VALVE-CONTROLLER
2 Valve Electronic Water Management System (Beta)

THIS IS A WORK IN PROGRESS!
Thingiverse link:
https://www.thingiverse.com/thing:4738765

I will continue to support this design based on user feedback; this means if no one is particularly interested, I will update only as I create new revisions to meet my personal project needs. If you have any questions, concerns, comments please feel free to message me and I will get back to you!
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Remaining Uploads:

BOM
Assembly Instructions
PCB Schematic (Via Github link)
Arduino Code (Via Github)
Reference Build Images (Host TBD)
This design is part of my goal: Developing consumer-grade garden automation products. If you happen to know of anyone within a related field I would be very interested to speak with you!
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
I currently run multiple reef/freshwater aquariums as well as a few aquaponic systems, all requiring a steady supply of RO water. Initially, I would connect each water storage tank to my filtration system, to replenish water lost. This proved troublesome, as I would need to time the fill rate and intercept the filtration system to prevent overflows. As this was annoying in the long run, the solution was to modify each container and install float valves that meter the flow once the container is full. This was ideal to prevent the container from overfilling, however, it still allowed the RODI system to accept water from the mainline, dumping excess "wastewater" until I was able to interfere and shut down the system. The design discussed on this page aims to rectify the problems mentioned above with an all in one monitor/valve system.

This is the initial release of a 2 valve electronic water management system; Intended to be used as a pre and post RO filtration controller, the design is however flexible. Modify the included parasolids, add your own code and you can turn this into a general-purpose 2 valve controller. Based on an Arduino Nano microcontroller, the system (as currently available) monitors a two-wire sensor line (float sensor) to regulate water flow into a reservoir of choice. For my RO filter application, the primary valve controls the mainline water flow while the secondary controls post-filtration flow. To put it simply:

Water level drops, triggering float sensor state ==> Valve 1 opens, pressurizing your input line ==> Valve 2 opens, releasing water into the reservoir.

The designated water level is achieved ==> Valve 1 closes, depressurizing filtration system ==> valve 2 closes, sealing off the reservoir from the input (valve 2) line.

This system is hopefully applicable to any and all applications where continuously recharged reservoirs are in need of a simple, automated DIY solution. Examples of use include:

Aquaponics
Hydroponics
General gardening (indoor/outdoor)
Aquarium keeping
RODI system management
etc...

The finished unit is portable, light and is designed to be retained (fastener-free) by a mechanically fastened mounting plate for ease of installation.

This design is intended to be a relatively affordable, simple and easy to print electronics project. Remix as required to add a secondary sensor, extra valves, etc. I have uploaded the most current Parasolid assembly file so feel free to dive into the geometry as you like!
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Please Note!

This design utilizes a prototyped PCB, check the included images to understand the scope of development work involved. There is plenty of interior volume within the PCB containment area, so it may be possible to revise the PCB mounting card to instead utilize a prototyping breadboard and related hardware. Check the related Parasolid file(s) to revise as needed.

I will be working on a one-off PCB design as time allows, which will be available off of PCBWay for those that would like a more accessible option. The schematic, Gerber files and BOM will also be uploaded here, and on Github, as I continue tinkering. Please either check back here for PCB availability or message me directly!
