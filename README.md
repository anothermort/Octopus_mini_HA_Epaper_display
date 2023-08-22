# Octopus_mini_HA_Epaper_display
An epaper display showing Octopus Mini data available from Home Assistant using ESPhome

The display is controlled by an ESP32, the display is a Waveshare 2.9" e-paper display

Requirements
This project pulls data from the Home Assistant integration created by BottlecapDave

https://github.com/BottlecapDave/HomeAssistant-OctopusEnergy

Connect your display to your ESP32 as via the pins in yaml
Copy yaml into ESPhome and install on ESP32

Data displayed currently

Current battery SOC % from Victron system
Current local tome

Electricity kWh used today
Gas kWh used today

Cost Electricity used today including standing charge
Cost Gas used today including standing charge
