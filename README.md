# Desi-Mochi-OTA-Updates
==============================
Desi-Mochi or Mochi-Keychain =
==============================

Version 1.2
* Modularized the Code
* Background Effects have random spead and patterns based on each expression
* Add LOVING Expression with Heart beat pattern, the eye and mouth are Heart Shaped

Version 1.3
* Adding Indian character symbols like Shiva's Third Eye with falling Trishul streams, Hanuman's Energetic Tilak,
    Vishnu's Royal tilak, and Brahma's Crown arcs cascading with sacred aura backgrounds.

Version 1.3.1:
* Add Speaker/Buzzer to the Project - GPIO2
* Added HappyBirthday tune, and this possible with Active Buzzer speaker

Version 1.3.2:
* Add touch Sensor TTP223
* Introduced a Menu with Modular tabs to choose different settings. One touch navigate through menus and Long touch
    to select the option, One touch then to change values, again Long touch to de-select the option.

Version 1.4:
* Adding advanced features like CLOCK + WEATHER + FACE Modes
* Touch State Engine as below:
    - Triple Tap: Toggles the Settings Menu
    - Double Tap: Instantly rotates to next application screen (Face -> Smart Clock -> Weather Forecast -> Face)/
    - Single Tap: Moves Rows inside the Menu (if Menu is Open) or Triggers a saccade eye roll look-around (if Menu is Closed)

Version 1.4.1:
* Add Automatic sync of time and weather from NTP and Openweather API
// =======================================================
  // --- NEW WEATHERAPI.COM SECURE API PATH ENDPOINT ---
    #define WEATHER_API_KEY "e64a6d1a9e224526a5299947261108"   // Replace with your OpenWeatherMap free API key
    #define WEATHER_CITY    "Bengaluru" //Define your city name using URL-safe formatting (use %20 if your city has spaces, like "New%20York")

Version 1.5:
* Make WiFi configuration Dynamic
* Fixed the Weather Text to display in two rows towards right bottom side
* Fixed Wifi connection with AP (Accesspoint) and move on to live mode.
* Added Brightness control in Settings Menu.
* Fixed SSD1306 hardware compatible along with SH1106 code bug
* Auto adjust brighness to 10% upon idle for a minute, means no touch.

Version 1.6:
* Enable OTA (Over the Air) functionality.
* Enhance the WiFi Captive Portal webpage with scanning available 2.4GHz access points (SSID) to choose while wifi setup.
* Enable Github Software Update Function using OTA option.


