# Community Portals
A huge shout out to EVERYONE involved with this project! From it's creation to the countless portals added!<br>
I am merely sharing the portals and the knowledge along with them. Feel free to head over to <a href=http://www.example.com>Example</a>  

## Limitations

The ESP32 access point will not have internet access while hosting the portal, as a result there cannot be any requests for stylesheets or javascript such as CDNs for bootstrap and JQuery.

All HTML/CSS/JS must be in a single HTML file. This is due to the fact that the index.html kept in the memory of the esp32.

There is a 20k character limit for each HTML file.

The form data must be sent to the `/get` endpoint as a GET request with the params `email` & `password`. You can put any information you want in these two fields. For example the `email` param can contain a username instead, just keep the param name as `email`.

Please check the example `index.html` to get an idea of what this has to look like. 


## Contributors

Thank you so much to the following contributors for providing awesome portals. 

- `Google_Modern.html` by [roshanravan](https://github.com/roshanravan)
- `Twitter.html` by [roshanravan](https://github.com/roshanravan)
- `Facebook.html` by [roshanravan](https://github.com/roshanravan)
- `CoxWifi.html` by [qqmajikpp](https://github.com/qqmajikpp)
- `Starlink.html` by [roshanravan](https://github.com/roshanravan)
- `Spectrum.html` by [roshanravan](https://github.com/roshanravan)
- `T_Mobile.html` by [roshanravan](https://github.com/roshanravan)
- `Verizon.html` by [roshanravan](https://github.com/roshanravan)
- `at&t.html` by [roshanravan](https://github.com/roshanravan)
- `southwest_airline.html` by [roshanravan](https://github.com/roshanravan)
- `delta_airline.html` by [roshanravan](https://github.com/roshanravan)
- `united_airline.html` by [roshanravan](https://github.com/roshanravan)
- `american_airline.html` by [roshanravan](https://github.com/roshanravan)
- `Jet_Blue.html` by [roshanravan](https://github.com/roshanravan)
- `Better_Google_Mobile.html` by [breaching](https://github.com/breaching)
- `AlaskaAirline.html` by [roshanravan](https://github.com/roshanravan)
- `Amazon.html` by [roshanravan](https://github.com/roshanravan)
- `FakeHack.html` by [roshanravan](https://github.com/roshanravan)
- `FakeHack2.html` by [roshanravan](https://github.com/roshanravan)
- `Matrix.html` by [roshanravan](https://github.com/roshanravan)
- `Microsoft.html` by [roshanravan](https://github.com/roshanravan)
- `Prank_Game.html` by [roshanravan](https://github.com/roshanravan)
- `SpiritAirlines.html` by [roshanravan](https://github.com/roshanravan)
- `Twitch.html` by [roshanravan](https://github.com/roshanravan)
- `apple.html` by [Jules](https://github.com/jules0835)
- `Frequency.html` by [roshanravan](https://github.com/roshanravan)

## Please use responsibly

## SD Setup for CM-Box
If you flashed from the <a href=https://atomnft.github.io/CM-Box/flash0.html>Custom Marauder Flasher tool for CYD</a> or built from <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder>CYD-ESP32Marauder</a> then You must create a folder on the root of your sd card titled "portals". This is where you will store the <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff>Evil Portal html files</a> along with the index.html file.

