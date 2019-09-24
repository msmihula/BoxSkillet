# Using the Box Skillet

The Box Skillet consists of one card for running with PAN-OS firewalls and a second card when using with a 
Panorama central management station.  When selected a the screen will display a series of prompts for information
related to deploying the Box rules and whether you want to allow or deny a particular function.

### PAN-OS
For working with PAN-OS firewalls select the Go button on the card labeled "Box Visibility and Control in PAN-OS."
This will bring up the PAN-OS Configuration screen and you will be prompted for information related to creating 
security rules to control Box traffic.

The first prompts are for source and destination zone that will be used to determine the zone context for the 
security rules that will be created to control Box traffic.  This is a free form entry field and there are a few
caveats to be aware of:
- The zone name entered must already exist
- Zone names are case sensitive

### Panorama
For working with Panorama systems select the Go button on the card labeled "Box Visibility and Control in Panorama."
This will bring up the Panorama Configuration screen.