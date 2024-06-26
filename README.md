# iSpindel-Stat
Thermostat Control of ordinary inexpensive heaters using iSpindel data. iSpindels are used in home brewing to wirelessly read specific gravity and temperature of the brew in real-time.

To make use of this project, you first need an iSpindel, and with it, a cloud account with Brew-Spy.  This is free.  

The final device will read the data you already send from your iSpindel too brew-Spy, and use the temperature component to decide to turn a heater on or off.  This could be an aquarium-style heater, a heating pad, or a space heater.  

It will allow you to maintain an ideal brewing temperature of 20 Degrees C.

You'll also need to know how to install and setup Arduino code platform and ESP32 libraries, and ensure that they work with the chosen display which comes on the ESP32 board.

There is no need to provide your Brew-Spy account details, as your Brew-Spy account already publishes your existing iSpindel data, anonymously, but 
accessible nonetheless.

I plan to add other services beyond Brew-Spy.

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

The chip needs power, 5 volts, so I chose this, due to its tiny size.

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="psu.png">
 <source media="(prefers-color-scheme: light)" srcset="psu.png">
 <img alt="PSU" src="PSU">
</picture>

All this needs to be crammed into a typical 2 or 3-gang extension block.  I got this one from eBay, and the black looks better, IMO.

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="plug.png">
 <source media="(prefers-color-scheme: light)" srcset="plug.png">
 <img alt="Plug" src="Plug">
</picture>

The left-hand socket will be used for powering the heater.  It will be up to you to open up and mount the chip, relay, and power unit, in the space within.  It is beyond the scope of this instruction.  I cut a hole in it, and 3d-printed a nice cover plate.  I have provided details of how I did this.
 
[UNDER CONSTRUCTION - MORE TO FOLLOW]
