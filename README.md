# Octopus_mini_HA_Epaper_display
An epaper display showing Octopus Mini data available from Home Assistant using ESPhome

The display is controlled by an ESP32, the display is a Waveshare 2.9" e-paper display

**Requirements**
This project pulls data from the Home Assistant integration created by BottlecapDave

https://github.com/BottlecapDave/HomeAssistant-OctopusEnergy

To be a customer of Octopus Energy

Ideally have an Octopus Mini

Home Assistant Setup with ESPHome

**Setup**
Connect your display to your ESP32 as via the pins in yaml
Copy yaml into ESPhome and install on ESP32

**Data displayed currently**

Current battery SOC % from Victron system

Current local time

Electricity kWh used today

Gas kWh used today

Cost Electricity used today including standing charge

Cost Gas used today including standing charge

**To Do**

Start up Splash screen

Allow dsiplay of larger values of cost and kWh usage.

**Screen Shot of current version**
![octo_mini_ihd](https://github.com/anothermort/Octopus_mini_HA_Epaper_display/assets/13786570/8ec0d6b5-a538-4f6d-b943-ccaa1fdc46f6)

