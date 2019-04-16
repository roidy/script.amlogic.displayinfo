# script.amlogic.displayinfo
Gets display info from Amlogic hardware.

Run this script in the `<onload>` of any window, ideally DialogPlayerProcessInfo.xml using 

`<onload>RunScript(script.amlogic.displayinfo)</onload>`

Then script will read /sys/class/amhdmitx/amhdmitx0/config and parse out the information to the following Window Info Labels:-

Window(10000).Property(amlogic.hdmitx.displaymode)  
Window(10000).Property(amlogic.hdmitx.colourdepth)  
Window(10000).Property(amlogic.hdmitx.colourspace)  
Window(10000).Property(amlogic.hdmitx.colourrange)  
Window(10000).Property(amlogic.hdmitx.eotf)  
Window(10000).Property(amlogic.hdmitx.colourimetry)  

USE AT YOUR OWN RISK.
