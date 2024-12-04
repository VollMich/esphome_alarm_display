# ESPHome alarm display
this display reads the state of you home_alarm and displays it on a heltec wifi kit 8 accordingly

## Variables To configure
- your Fallback Hotspot username
- your Fallback Hotspot password
- your Webserver username
- your Webserver password
- your API password
- your OTA password
- your Outdoor Temperature Sensor

## This file was written for an ESPHome 2024.6.6
Newer Versions of ESPHome have other API and OTA logic. If you use a newer version of ESPHome You can add a new device, let ESPHome create API and OTA passwords for you and then merge this file into your new template.

## Specials
- if home_alarm is inactive, the display does not display this information, it displays the outdoor temperature instead
- 180° Display rotation from within Home Assistant from configuration page, flash persisted
