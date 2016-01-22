# Fibaro-Dimmer-211
SmartThings Device type for Fibaro Dimmer 211
I have final cobbled together a device type handler for the Fibaro Dimmer 211 which includes the ability to change the parameters. I have struggled trying to change parameters on this unit and could not find any code that actually worked. So I set about creating something that would.
It's not the most elegant solution but it works (for me anyway) and once you have the parameters set  up exactly as you want them you can revert back to your previous DTH if you prefer as the 211 unit should retain it's settings.

Log in to the Developers website and click My Device Handlers. 
Click +New Device Handler then select From Code.
Copy the Device type code and paste it into your New Device Handler then click Create.

To change a parameter value you need to change it in the code. Scroll down the code to the INSTRUCTIONS section and you should be able to read what to do. Here's a snapshot of what you'll see
****************************************************************************************************************
**************                                  INSTRUCTIONS                                      **************
****************************************************************************************************************
**************  Change the Parameter configurationValue[] in the code below to  the value         **************
**************  you want.(Refer to manual for defaults and valid values). Then Save your changes  ************** 
**************  and Publish For Me. Then open SmartThings App and select your device.             ************** 
**************  Click 3 dots top right(Android app) & Edit Device then click Done. This triggers  **************
**************  the Update. If you want to confirm  the parameter change then monitor             **************
**************  Live Logging on developers web site and click Configure in the SmarthThings App.  **************
*************   this will give you a report of each of the device's parameters and its current    **************
*************   value and size.                                                                   **************
*************   Once you have changed the parameter you can switch back to your original Device   **************
*************   type if you prefer as the parameter change is retained in the 211 device.         ************** 
*************   I've only listed some parameter below there are others. Just add them if you wish ************** 
*************              Not elegant coding I know but at least it seems to work.               ************** 



As I can now change parameters I feel I have finally tamed this unit.

Hope it works for you.

