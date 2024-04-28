![Header](pictures/mainheader.png)
<br>

## 🌟 Update Highlights 04/28/24 🌟
<b>Wi-Fi Marauder has been updated to 13.10 These files refelect the new changes and updates!</b>
<br>
<b>RGB is now working for sniffing and attacks thanks to <a href=https://github.com/lsdlsd88>lsdlsd88</a> and <a href=https://github.com/Fr4nkFletcher>Fr4nkFletcher</a> </b>

<hr>
<br>


<b>A beautiful fork of wifi Marauder 13.10, a suite of WiFi/Bluetooth offensive and defensive tools for the 2.8'' ESP32 Module ESP32-2432S028R WiFi+BT Dual-core 240X320 Smart Display.</b>
<b>This fork features a few great fixes and customzations.</b>
  
  <br>
  
  
## To build this fork of Marauder from source

- Head over to <a href=https://github.com/smoochiee/Marauder-FOR-CYD---CHEAP-YELLOW-DISPLAY>smoochiee's tutorial</a> and start from step 1 in his tut.
- When you get to the "LIBRARIES" section you can use the libs he has linked or the ones in this repo which are the same.
- Now on the step in smoochiee's tutorial where he mentions to download the source code for Marauder, use the files from <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/esp32_marauder>esp32_marauder</a> instead (These files contain the sketch edits already). Then head back to <a href=https://github.com/smoochiee/Marauder-FOR-CYD---CHEAP-YELLOW-DISPLAY>smoochiee's tutorial</a> and Follow the rest of the steps provided by the legend himself and you should be good to go. I will be adding my own tutorial for flashing this build to your CYD very shortly.

<br>

## Web-flasher tool
 <a href=https://atomnft.github.io/CM-Box/flash0.html>Custom Marauder Flasher tool for CYD</a>
 <b>Instructions are simple. Choose your hardware, and then hit connect.</b>
  
  <br>
  <br>
  <br>
  
  
## Fixes (These are included in this fork)
  
  - `BLE swift pair fix` [BLE FIX](https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/BLE%20Swiftpair%20Fix)

  - `Evil Portal storage fix` [Evil Portal SD fix](https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff)
 
 <br>
 
## SD portal fix
  <b> This fix is to relocate all the portals for evil portal to a folder on the sd card. When you install Marauder on the CYD all the protals used in evil portal get stored on the root of the sd card. To me this is a nuisance as all the pcap and other files that are captured while sniffing get thrown on the root of the sd as well. I have gone through and adjusted the code so you may create a folder titled "portals" and store the html files there.<br>In the <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff>Evil Portal</a> section are the files needed along with directions on usage. </b>
 
 <br>
 <br>
 <br>

<b>A huge thank you goes to two wonderful people. Whom without I would have not made it as far as I  did learning.</b> <br>
<b>Thanks to <a href=https://github.com/Fr4nkFletcher>Fr4nkFletcher</a> for all your guidance and late night replies.</b>
<b>And thank you to <a href=https://github.com/smoochiee>smoochiee</a> for helping with the bootscreen and the badass tuts for building our own Marauder.</b>
<b>Also thanks to 3DJoe for figuring out the touch functions for marauder on the CYD..</b>
<br>


  
  
  