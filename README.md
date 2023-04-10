# Higrow Esphome
esphome configuration for TTGO HiGrow BME280 version

## Features
Provide the following sensors:
* Charging status
* Battery voltage
* Battery percentage
* Soil salt level
* Soil moisture level
* Illuminance
* Temperature
* Humidity
* Pressure

When plugged in, the device will remain online and update the sensors every 60secs.  
When unplugged, the device will go to deep sleep every 60mins, and the battery will last for 7 to 10 days.



## Deploy
```esphome run higrow.yaml```  
