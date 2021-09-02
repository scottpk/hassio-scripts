# Some Scripts Created for Home Assistant
These are some scripts I've created during my ongoing home automation attempts. There is no promise they will work with your setup, work as intended, etc - but feel free to use them.
## Set Thermostat Based on Real-Feel
Set the thermostat based on an approximation of perceived temperature. The calculation is based off a formula for calculating heat index. Requires a thermostat and at least one hygrometer. Send in a temperature sensor to bias the thermostat's setting according to this sensor (I recommend using min_max or something similar).
## Set Hue to Color Loop
This is for Zigbee2MQTT, to set your Philips Hue bulb to Color Loop. It just publishes the `hue_move` command. Make sure you replace my lamp name with whatever the name of yours is.