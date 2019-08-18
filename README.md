# Home Assistant config

This is my Home Assistant configuration.
I try to connect most of the hardware and services that I often use. We use the iOS app to manage and find the information we need. The goal is to automate what we can, but also to have one stop where we find all the information about the house, weather, cars, activity etc.
The setup is running a Raspberry Pi 3 Model B.


### Hardware

*  [Ikea Trådfri](https://www.ikea.com/no/no/p/tradfri-gateway-hvit-40337806/)
*  [Google Home](https://store.google.com/product/google_home)
   *  [Google Home](https://store.google.com/product/google_home)
   *  [Google Mini](https://store.google.com/product/google_home_mini)
   *  [Chromecast](https://store.google.com/product/chromecast)
   *  [Chromecast Audio](https://www.google.com/intl/no_no/chromecast/audio/buy/)
*  [AEON Z-Stick](https://aeotec.com/z-wave-usb-stick/)
   *  [Danalock V3 (+ Danapad, not connected to HA)](https://danalock.com/products/danalock-v3-smart-lock/)
*  [Sensibo](https://sensibo.com/)
*  [Mill NE1000L WIFI](https://www.millheat.com/mill-wifi/ne1000l-wifi-jrxw9)
*  [Tibber Pulse](https://norge.tibber.com/products/pulse/)
*  [Netatmo Weather Station](https://www.netatmo.com/no-no/weather/weatherstation)
*  [Fitbit Aria 2](https://www.fitbit.com/aria2)
*  Nissan Leaf 2.0
*  Volkswagen e-UP


### Connected Services
*  [Pi-Hole](https://github.com/hassio-addons/addon-pi-hole/tree/v3.0.2)
*  [Google Cloud Backup](https://github.com/sabeechen/hassio-google-drive-backup)
*  [Google Calendar](https://www.home-assistant.io/components/calendar.google/)
   *  Garbage Collection
   *  Working Schedule
   *  Personal Schedule
*  [Met.no](https://www.met.no/)
*  [Nabu Casa](https://www.nabucasa.com/)
*  [Spotify](https://www.spotify.com/us/)
*  [Tibber](https://norge.tibber.com/)
*  [iOS App](https://www.home-assistant.io/docs/ecosystem/ios/)

### [HACS Custom Elements](https://github.com/custom-components/hacs)
*  [Spotcast](https://github.com/fondberg/spotcast)
*  [iCal Sensor](https://github.com/tybritten/ical-sensor-homeassistant)
*  [iPhone Device Tracker](https://github.com/mudape/iphonedetect)
*  [Atomic Calendar](https://github.com/atomic7777/atomic_calendar)
*  [Lovelace Slider Entity Row](https://github.com/thomasloven/lovelace-slider-entity-row)
*  [Mini Graph Card](https://github.com/kalkih/mini-graph-card)
*  [Mini Media Player](https://github.com/kalkih/mini-media-player)
*  [Simple Thermostat](https://github.com/nervetattoo/simple-thermostat)
*  [Weather Card](https://github.com/bramkragten/weather-card)


### Automations

*  Heating and Cooling with AC
*  Lock / Unlock frontdoor
*  Notifications with TTS and Push
   *  Garbage Collection
   *  ETA after leaving work
   *  Charging car reminder
