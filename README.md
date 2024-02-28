# iSpindel-Thermostat
Control of heaters using iSpindel devices and heaters or standard heat pads.

To make use of this project, you first need an iSpindel, and with it, a cloud account with Brew-spy.  This is free.  
The final device will read the data you already send via your iSpindel, and use the temperature component to decide to
turn a heater on or off.  This could be an equarium-style heater, a heating pad, or a space heater.

There is no need to provide your Brew-SPy account details, as your Brew-Spy account already publishes it, anonymously, but 
accessible nonetheless.

In short, you use an ESP32 chip, with a built-in display, a realy, and a small transformer, cram it all into a 2-way extension plug, then configure it to work with your iSpindel.

You can get the required chips from ALi Express, eBay or Amazon.  I chose this one:

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="esp.png">
 <source media="(prefers-color-scheme: light)" srcset="esp.png">
 <img alt="YOUR-ALT-TEXT" src="YOUR-DEFAULT-IMAGE">
</picture>

 
