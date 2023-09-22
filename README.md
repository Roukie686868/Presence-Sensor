# Presence-Sensor

##Purpose
Purpose of this project is to create a low cost sensor that tells if there is somebody in the room or not. The sensor used in the project is the LD2410 24 gHz sennsor from Hi-Link. According the supplier the longest distance for sensing is up to 5 meters.
This sensor does not rely on motion, instead it "sees" a person. The precense is reported via a digital signal to an ESP8266 that runs either Tasmota or ESPhome. For the setup in Home Assistant the example will be explaned making use of Tasmota. A second (serial) signal from the ESP8266 give a distance reading on the person. 

![Home Assitance View](https://github.com/Roukie686868/Presence-Sensor/blob/main/Documents/Pictures/HA.PNG)

