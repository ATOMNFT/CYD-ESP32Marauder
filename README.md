![Header](pictures/mainheader.png)
<br>


<div align="center" style="max-width: 100%; overflow: visible;">
  <img 
    src="https://github.com/ATOMNFT/CM-Box/blob/main/Images/Repolike.svg" 
    style="width: 100%; height: 110px; max-width: 800px;" 
    alt="Responsive SVG">
</div>
  
---

  ## ⬆ Update Highlights 1/11/25 ⬆ <br> Added New v1.2.0!
  
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

> ## 💾 **SD Portal Fix** 💾
> 
> This fix relocates all portals for Evil Portal to a dedicated folder on the SD card.  
> When you install Marauder on the CYD, all the portals used in Evil Portal are stored on the root of the SD card. This can be a nuisance as PCAP and other files captured during sniffing also clutter the root directory.  
> 
> With this update, you can create a folder titled `portals` to store the HTML files.  
> Visit the [Evil Portal](https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff) section for the necessary files and detailed usage instructions.  
> 
> ---
> 
> ## **SD Setup for CM-Box**
> 
> If you flashed from the [Custom Marauder Flasher Tool for CYD](https://atomnft.github.io/CM-Box/flash0.html)  
> or built from [CYD-ESP32Marauder](https://github.com/ATOMNFT/CYD-ESP32Marauder), you must create a folder on the root of your SD card titled `portals`.  
> 
> This is where you will store the [Evil Portal HTML files](https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff), including the `index.html` file.

 
<hr>
<br>

> ## 🔧 **Building This Fork of Marauder from Source** 🔧  
> 
> Follow these steps to build this fork of Marauder for your CYD module:  
> 
> ### Step 1: Start with Smoochiee’s Tutorial  
> Head over to [Smoochiee's tutorial](https://github.com/smoochiee/Marauder-FOR-CYD---CHEAP-YELLOW-DISPLAY) and begin from Step 1.  
> 
> ### Step 2: Libraries Setup  
> When you reach the **"LIBRARIES"** section:  
> - You can use the libraries linked in Smoochiee's tutorial.  
> - Alternatively, use the libraries provided in **this repository**, as they are identical.  
> 
> ### Step 3: Use Modified Source Files  
> On the step where Smoochiee directs you to download Marauder's source code:  
> - Instead of the original files, download the pre-modified files from one of the following:  
>   - [CYD ESP32 Marauder 13.10 (NoGPS)](https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/CYD%20ESP32%20Marauder%2013.10%20(NoGPS))  
>   - [CYD ESP32 Marauder 1.0.0 (NoGPS)](https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/CYD%20ESP32%20Marauder%201.0.0%20(NoGPS))
>   - [CYD ESP32 Marauder 1.1.0 (NoGPS)](https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/CYD%20ESP32%20Marauder%201.1.0)
> These files include all necessary sketch edits.  
> 
> ### Step 4: Complete the Tutorial  
> Return to [Smoochiee's tutorial](https://github.com/smoochiee/Marauder-FOR-CYD---CHEAP-YELLOW-DISPLAY) and continue with the remaining steps.  
> 
> ---
> 
> ### Coming Soon: My Custom Tutorial  
> I’ll soon be adding my own guide for flashing this build to your CYD module. Stay tuned!

<br>
<hr>

## ⚡ Web-Flasher Tool for Simple Installation ⚡

🚀 **Flash Your CYD Module with Ease**  
Use the [Custom Marauder Flasher Tool for CYD](https://atomnft.github.io/CM-Box/flash0.html) to quickly and effortlessly flash your device.  

### How It Works:  
1️⃣ **Select Your Hardware**: Choose the correct CYD model from the dropdown menu.  
2️⃣ **Connect**: Click the **"Connect"** button to start the flashing process.  
3️⃣ **Done**: The tool will handle everything for you!  

🎉 With this tool, flashing your CYD has never been simpler or faster.
  
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
