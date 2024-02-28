# iSpindel-Thermostat
Control of heaters using iSpindel devices and heaters or standard heat pads.

To make use of this project, you first need an iSpindel, and with it, a cloud account with Brew-spy.  This is free.  
The final device will read the data you already send via your iSpindel, and use the temperature component to decide to
turn a heater on or off.  This could be an equarium-style heater, a heating pad, or a space heater.

There is no need to provide your Brew-Spy account details, as your Brew-Spy account already publishes your existing iSpindel data, anonymously, but 
accessible nonetheless.

In short, you use an ESP32 chip, with a built-in display, a relay, and a small transformer, cram it all into a 2-way extension plug, then configure it to work with your iSpindel.

You can get the required chips from Ali Express, eBay or Amazon.  I chose this one:

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="esp.png">
 <source media="(prefers-color-scheme: light)" srcset="esp.png">
 <img alt="ESP" src="ESP">
</picture>

As for relays, these will do the job:
<picture>
 <source media="(prefers-color-scheme: dark)" srcset="relay.png">
 <source media="(prefers-color-scheme: light)" srcset="relay.png">
 <img alt="Relay" src="Relay">
</picture>



 
