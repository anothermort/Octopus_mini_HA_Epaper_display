# Octopus_mini_HA_Epaper_display

An epaper display showing Octopus Mini data available from Home Assistant using ESPhome

The display is controlled by an ESP32, the display is a Waveshare 2.9" e-paper display

**Requirements**

This project pulls data from the Home Assistant integration created by BottlecapDave

https://github.com/BottlecapDave/HomeAssistant-OctopusEnergy

To be a customer of Octopus Energy

Have an Octopus Mini

Home Assistant Setup with ESPHome

[ESP32 £7 from Amazon](http://www.amazon.co.uk/dp/B071JR9WS9/ref=nosim?tag=anothermort-21) programmed  via ESPhome

[Waveshare 2.9" E Paper screen £25.99 from Amazon ](http://www.amazon.co.uk/dp/B071LGVVL1/ref=nosim?tag=anothermort-21)
** Amazon affiliate links you will not be charged anymore than standard price but I will get a small commision on any purchase. **

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

Pulls data every 60 seconds.

**To Do**

Start up Splash screen

Allow display of larger values of cost and kWh usage.

Make a case for display and ESP32 

**Screen Shot of current version**
![octo_mini_ihd](https://github.com/anothermort/Octopus_mini_HA_Epaper_display/assets/13786570/8ec0d6b5-a538-4f6d-b943-ccaa1fdc46f6)








**If you would like to switch to Octopus Energy you can support me.
A friends & family link is below and we split £100 credit if you join through the unique link:
https://share.octopus.energy/melon-rook-819** 

