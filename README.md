![Header](pictures/mainheader.png)
<br>


<p align="center">
  <img src="https://github.com/ATOMNFT/CM-Box/blob/main/Images/Repolike.svg">
  </p>
  
---

  ## ⬆ Update Highlights 11/23/24 ⬆ <br> Added New v1.1.0!
  
  | Feature/Update                             | Description/Notes                                                                                                                                                        |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| • Added logging to SD for Flipper/AirTag sniff | Thanks to Fr4nkFletcher                                                                                                                                               |
| • Added Pcap capture of flipper data       | WIP as the pcap is malformed                                                                                                                                            |
| • Added Flipper Zero Sniff                 |                                                                                                                                                                        |
| • Airtag Sniffing/Spoofing                 |                                                                                                                                                                        |
| • Working Pwnagotchi Detect on all models  |                                                                                                                                                                        |
| • Flipper BLE Spam                         |                                                                                                                                                                        |
| • Wardriving Menu added                    |                                                                                                                                                                        |
| • RGB LED enabled                          | Thanks to lsdlsd88                                                                                                                                                    |
| • Detect Pwnagotchi 100% functional        |                                                                                                                                                                        |
| • BLE/SwiftPair Spam now 100% functional   |                                                                                                                                                                        |
| • Evil Portal storage adjustment           | Moves all portals into a folder instead of root of SD card                                                                                                            |
| • External antenna information             | [Click here](https://github.com/Fr4nkFletcher/ESP32-Marauder-Cheap-Yellow-Display/blob/master/AntennaMod.md) for info on adding an external antenna.                                                                                                                |

---

<b>For more of the changes and additions to marauder, head over <a href=https://github.com/justcallmekoko/ESP32Marauder/releases/tag/v1.1.0>HERE</a> And read more</b>

<br>

<b>A beautiful fork of wifi Marauder, a suite of WiFi/Bluetooth offensive and defensive tools for the 2.8'' ESP32 Module ESP32-2432S028R WiFi+BT Dual-core 240X320 Smart Display.</b>
<b>This fork features a few great fixes and customzations.</b>

<hr>
<br>
  
> ## 🛠️ **Device Compatibility**
> 
> Successfully tested on:
> - [CYD variant 1](https://amazon.com/dp/B0BVFXR313)  
> - [CYD variant 2](https://amazon.com/dp/B0CLR7MQ91)  
> 
> **✨ No hardware modifications required!**  
> This is made possible thanks to seamless integration with **[@ggaljoen](https://github.com/ggaljoen)'s** [TFT_eSPI](https://github.com/ggaljoen/TFT_eSPI) fork.

<hr>

> ## 📡 **GPS Functionality** 📡
> 
> - **GPS is enabled** on builds `13.10` & `1.0.0` (not labeled as "NoGPS" in the flasher tool).  
>   It is fully operational via the 4-pin connector located near the MicroUSB port on the CYD module.  
> 
> - For build `1.1.0`, GPS is fully functional with **no conflicts** affecting LED or Pwnagotchi detection.  
> 
> 🔗 [Check here](https://github.com/justcallmekoko/ESP32Marauder/wiki/gps-modification) for details on supported GPS hardware.

<hr>
<br>

## 💾 SD portal fix 💾

  <b> This fix is to relocate all the portals for evil portal to a folder on the sd card. When you install Marauder on the CYD all the protals used in evil portal get stored on the root of the sd card. To me this is a nuisance as all the pcap and other files that are captured while sniffing get thrown on the root of the sd as well. I have gone through and adjusted the code so you may create a folder titled "portals" and store the html files there.<br>In the <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff>Evil Portal</a> section are the files needed along with directions on usage. </b>
  
  ## SD Setup for CM-Box
If you flashed from the <a href=https://atomnft.github.io/CM-Box/flash0.html>Custom Marauder Flasher tool for CYD</a> or built from <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder>CYD-ESP32Marauder</a> then You must create a folder on the root of your sd card titled "portals". This is where you will store the <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff>Evil Portal html files</a> along with the index.html file.
 
<hr>
<br>
  
## 🔧 To build this fork of Marauder from source 🔧

- Head over to <a href=https://github.com/smoochiee/Marauder-FOR-CYD---CHEAP-YELLOW-DISPLAY>smoochiee's tutorial</a> and start from step 1 in his tut.
- When you get to the "LIBRARIES" section you can use the libs he has linked or the ones in this repo which are the same.
- Now on the step in smoochiee's tutorial where he mentions to download the source code for Marauder, use the files from  <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/CYD%20ESP32%20Marauder%2013.10%20(NoGPS)>CYD ESP32 Marauder 13.10 (NoGPS)</a> or <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/CYD%20ESP32%20Marauder%201.0.0%20(NoGPS)>CYD ESP32 Marauder 1.0.0 (NoGPS)</a> instead (These files contain the sketch edits already). Then head back to <a href=https://github.com/smoochiee/Marauder-FOR-CYD---CHEAP-YELLOW-DISPLAY>smoochiee's tutorial</a> and Follow the rest of the steps provided by the legend himself and you should be good to go. I will be adding my own tutorial for flashing this build to your CYD very shortly.

<br>
<hr>

## ⚡ Web-flasher tool for simple install ⚡
 <a href=https://atomnft.github.io/CM-Box/flash0.html>Custom Marauder Flasher tool for CYD</a>
 <br>
 <b>Instructions are simple. Choose your hardware, then hit connect to start the flashing process on your CYD</b>
  
  <br>
  <br>
 
## 📢 Shoutouts! 📢
<b>A huge thank you goes to two wonderful people whom without I would have not made it as far as I  did learning.</b> 
<br>
<b>Thanks to <a href=https://github.com/Fr4nkFletcher>Fr4nkFletcher</a> for all your guidance and late night replies.</b>
<br>
<b>And thank you to <a href=https://github.com/smoochiee>smoochiee</a> for helping with the bootscreen and the badass tuts for building our own Marauder.</b>
<br>
<b>Also thanks to 3DJoe for figuring out the touch functions for marauder on the CYD..</b>
<br>
And of course the man <a href=https://github.com/justcallmekoko>JustCallMeKoko</a>for the foundational work on ESP32 Marauder.
