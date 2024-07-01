![Header](Images/epheader.png)
<br>
  # Adjusted sd card portal storage
  <b>I have tweaked a section of two files (EvilPortal.cpp & SDInterface.h) to allow the portals used in EP to be stored in a folder on the sd card instead of just being stored in the root of sd card
  along with all the pcaps and other files captured.</b>
  
  ## SD Setup for CM-Box
  If you flashed from the <a href=https://atomnft.github.io/CM-Box/flash0.html>Custom Marauder Flasher tool for CYD</a> or built from <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder>CYD-ESP32Marauder</a> then You must create a folder on the root of your sd card titled "portals". This is where you will store the <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff>Evil Portal html files</a> along with the index.html file.
  
  <br>
 
  <b>The folder titled "portals is to be added to the root of your sd card. It contains the ap.config file, a file titled "index.html", and a few smaller sized portals. Download the zip file and unzip it. Drag or copy/paste the folder titled "portals" to the root of your sd card. </b>
  
  <br>
  
  <b>The sd adjustment/fix is included in <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master> this sketch for the CYD.</a>  if you plan to build from source</b>
 

