# iSpindel-Stat
Control of heaters using iSpindel devices and heaters or standard heat pads.

To make use of this project, you first need an iSpindel, and with it, a cloud account with Brew-spy.  This is free.  

The final device will read the data you already send via your iSpindel, and use the temperature component to decide to
turn a heater on or off.  This could be an aquarium-style heater, a heating pad, or a space heater.  
It will allow you to maintain an ideal brewing temperature of 20 Degrees C.

You'll also need to know how to install and setup Arduino code platform and ESP32 libraries, and ensure that they work with the chosen display which comes on the ESP32 board.

There is no need to provide your Brew-Spy account details, as your Brew-Spy account already publishes your existing iSpindel data, anonymously, but 
accessible nonetheless.

In short, you use an ESP32 chip, with a built-in display, a relay, and a small transformer, cram it all into a 2-way extension plug, then configure it to work with your iSpindel.

You can get the required chips and other parts from Ali Express, eBay or Amazon.  I chose this one:

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="esp.png">
 <source media="(prefers-color-scheme: light)" srcset="esp.png">
 <img alt="ESP" src="ESP">
</picture>


As for relays I chose the SRD-05 (5 volts). These will do the job:

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="relay.png">
 <source media="(prefers-color-scheme: light)" srcset="relay.png">
 <img alt="Relay" src="Relay">
</picture>


The chip needs, power, 5 volts, so I chose this (picture show 3.7 volt variant, but I got the 5 volt one), due to it's tiny size.

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="xformer.png">
 <source media="(prefers-color-scheme: light)" srcset="xformer.png">
 <img alt="Xformer" src="Xformer">
</picture>

All this needs to be crammed into a typical 2 or 3-gang extension block.  I got this one from eBay, and the black lools better, IMO.

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="plug.png">
 <source media="(prefers-color-scheme: light)" srcset="plug.png">
 <img alt="Plug" src="Plug">
</picture>

The left-hand socket will be used for powering the heater.  It will be up to you to open up and mount the chip, relay, and ppower unit in the space within.  It is beyond the scop of this instruction.  I cut a hole in it, and 3d-printed a nice cover plate.
 
[UNDER CONSTRUCTION]
