# Drone Live Backend Connection


live.api.rekari.de Port 8846 TCP

Needs to call ping (or any other function) every 5s to let socket stay open

## Message

{

  "type": {TYPE}
  ...

}

## Type

* "currentPosition"
 
  * "lat" (num)
 
  * "lon" (num)
 
  * "alt" (num)
 
  * "gpsNum" (num)
 
  * "horizontalAccuracy" (num)
 
  * "verticalAccuracy" (num)
  
* "currentBattery"
  
  * "voltage" (num)
  
  * "percentage" (num)
  
* "currentMode"
  * "emergencyStop" (bool)
  
  * "mode" (string)

* "auth"
  * "key" (string)
  
  * "uuid" (string)

* "ping"

  
 
 
