![Header](pictures/mainheader.png)
<br>



  <b>A beautiful fork of wifi Maraduer, a suite of WiFi/Bluetooth offensive and defensive tools for the 2.8'' ESP32 Module ESP32-2432S028R WiFi+BT Dual-core 240X320 Smart Display.</b>
  <b>This fork features a few great fixes and customzations.</b>
  
  <br>
  
  ## SD portal fix
  <b> This fix is to relocate all the portals for evil portal to a folder on the sd card. When you install marauder on the CYD all the protals used in evil portal get stored on the root of the sd card. To me this is a nuisance as all the pcap and other files that are captured while sniffing get thrown on the root of the sd as well. I have gone through and adjusted the code so you may create a folder titled "portals" and store the html files there.<br>In the <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff>Evil Portal</a> section are the files needed along with directions on usage. </b>
  
  
  
  ## To install this fork of marauder
  <b>Head over to <a href=https://github.com/smoochiee/MARAUDER-FOR-CYD---CHEAP-YELLOW-DISPLAY>smoochiee's tutorial</a> and start from step 1 in his tut. <br> 
When you get to the "LIBRARIES" section you can use the libs he has linked or the ones in this repo which are the same.</b>
<br>

Now on the step in smoochiee's tutorial where he mentions to download the source code for marauder, use the files from <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/esp32_marauder>esp32_marauder</a> instead. Then head back to <a href=https://github.com/smoochiee/MARAUDER-FOR-CYD---CHEAP-YELLOW-DISPLAY>smoochiee's tutorial</a> and Follow the rest of the steps provided by the legend himself and you should be good to go. I will be adding my own tutorial for flashing this build to your CYD very shortly.</b>

<br>

## Web-flasher tool
 <a href=https://atomnft.github.io/CM-Box/flash0.html>Custom Marauder Flasher tool for CYD</a>
  
  <br>
  <br>
  
  <b>A huge thank you goes to two wonderful people. Whom without I would have not made it as far as I  did learning.</b> <br>
  <b>Thanks to <a href=https://github.com/Fr4nkFletcher>Fr4nkFletcher</a> for all your guidance and late night replies.</b>
  <b>And thank you to <a href=https://github.com/smoochiee>smoochiee</a> for helping with the bootscreen and the badass tuts for building our own Marauder.</b><br>
  
  
  <br>
  <br>
  
  
  ## Fixes (These are included in this fork)
  
  - `Looking for BLE swift pair fix` [BLE FIX](https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/BLE%20Swiftpair%20Fix)

 - `Looking for Evil Portal storage fix` [Evil Portal SD fix](https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff)
 




  
  
  