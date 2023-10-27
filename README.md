# Presence-Sensor

## Purpose
Purpose of this project is to create a low cost sensor that tells if there is somebody in the room or not. The sensor used in the project is the LD2410 24 gHz sennsor from Hi-Link. According the supplier the longest distance for sensing is up to 5 meters.
This sensor does not rely on motion, instead it "sees" a person even if you don't move. The presence of a person is reported via a digital on/off signal to an ESP8266 that runs either Tasmota or ESPhome. A second (serial) signal from the ESP8266 gives a distance reading of the person. For the setup in Home Assistant this example will be explaned making use of Tasmota.  

Please see the full write up to set the unit up with Tasmota in the [following document ](https://github.com/Roukie686868/Presence-Sensor/blob/main/Documents/How%20to%20setup%20the%20Presence%20Sensor.docx).  
When you are a fan of ESPHome then follow this [document ]( https://www.digitaldomo.nl/configureer-esp-functie-voor-ld2410/).  

To Discuss issue you might have join me on this [Discord Channel - Presence Sensor ](https://discord.gg/D4hMt9rzSx)

The supplier of the HLK-LD2410 sensor is also providing an app to change the behaviour of the sensor. Click the link for the [Apple Version](https://apps.apple.com/us/app/hlkradartool/id1638651152)  or the [Android Version](https://apkpure.com/hlkradartool/com.hlk.hlkradartool)  
App Screenshot  
![HLK Radar Tool App](https://github.com/Roukie686868/Presence-Sensor/blob/main/Images/Screenshot%202023-09-23%20at%2020.53.53.jpeg)  

Screenshot of the view in Home Assistant.   
![Home Assitance View](https://github.com/Roukie686868/Presence-Sensor/blob/main/Documents/Pictures/HA.PNG)

