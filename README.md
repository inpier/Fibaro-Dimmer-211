# Fibaro-Dimmer-211
SmartThings Device type for Fibaro Dimmer 211.

I have final cobbled together a device type handler for the Fibaro Dimmer 211 which includes the ability to change the parameters. I have struggled trying to change parameters on this unit and could not find any code that actually worked. So I set about creating something that would.
It's not the most elegant solution but it works (for me anyway so use at your own risk). But once you have the parameters set  up exactly as you want them you can revert back to your previous DTH if you prefer as the 211 unit should retain it's settings.

****Word of Warning****
Having changed Parameter 14 to 1 i.e.Toggle Switch I found that after a short while the switch stopped working. I read somewhere that this was an issue with the 211 and that Parameter 10 should be set to 0 to solve this problem so I set it to 0 and it seems to have sorted it.

Method.
Log in to the Developers website and click My Device Handlers. 
Click +New Device Handler then select  the From Code option.
Copy the Device type code and paste it into your New Device Handler then click Create then Save and Publish for me.

Now select My Devices. Find your device and click to open its details. Click the Edit button at the bottom of the page and then
look for the drop down box marked Type*. The list will now include Fibaro Dimmer 211 params UK. Choose it and click Update.


To change a parameter value you need to change it in the code. Scroll down the code to the INSTRUCTIONS section and you can read what to do. 



Hope it works for you.

