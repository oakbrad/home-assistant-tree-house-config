# home-assistant-tree-house-config
The Tree House, an open source loft powered by [Home Assistant](https://www.home-assistant.io/), [Node-Red](https://nodered.org/), and [MQTT](http://mqtt.org/).

# Home Assistant Hub
A Rasperry Pi 3B, with a Z-Wave / Zigbee USB stick. HassIO version 0.82.1. Addons installed:

* [Node-Red](https://github.com/hassio-addons/addon-node-red) Visually construct automation logic
* [DuckDNS](https://www.home-assistant.io/addons/duckdns/) for encryption and external access
* [Configurator](https://www.home-assistant.io/addons/configurator/) For editing files on Pi hub
* [Samba](https://www.home-assistant.io/addons/samba/) Share Pi configuration files on local network
* [SSH](https://www.home-assistant.io/addons/ssh/) Connect to Pi for remote administration
* [Mosquitto](https://www.home-assistant.io/addons/mosquitto/) Lightweight telemetry for open source devices

The lights are powered by [esp8266_milight_hub](https://github.com/sidoh/esp8266_milight_hub). Sensors are powered by [esphomelib](https://esphomelib.com/).

Voice control is provided by [Home Assistant Cloud](https://www.nabucasa.com/), using Amazon Echo devices.

# Home Assistant Components
Documentation for all HA integrations used.

* [binary_sensor.bayesian](https://www.home-assistant.io/components/binary_sensor.bayesian/)
* [climate.generic_thermostat](https://www.home-assistant.io/components/climate.generic_thermostat/)
* [device_tracker.ios](https://www.home-assistant.io/docs/ecosystem/ios/)
* [device_tracker.ping](https://www.home-assistant.io/components/device_tracker.ping/)
* [light.mqtt](https://www.home-assistant.io/components/light.mqtt/)
* [media_player.chromecast](https://www.home-assistant.io/components/cast/)
* [media_player.roku](https://www.home-assistant.io/components/media_player.roku/)
* [proximity](https://www.home-assistant.io/components/proximity/)
* [switch.tplink](https://www.home-assistant.io/components/switch.tplink/)
* [weather.darky_sky](https://www.home-assistant.io/components/weather.darksky/)
* [zone](https://www.home-assistant.io/components/zone/)
* [zwave[(https://www.home-assistant.io/components/zwave/)
