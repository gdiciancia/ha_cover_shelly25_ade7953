# ha_cover_shelly25_ade7953
The following is an example configuration for controlling covers (like window blinds etc) with ESPHome. 
When power reaches a certain threshold, the respective endstop is triggered and the cover will automatically stop.
The power is measured by the ADE7953 sensor in the Shelly 2.5.

To protect the motors from spinning indefinitely (in case an endstop fails) the motors
also have a maximum configurable run time - after x seconds they will automatically turn off even if the
endstop is not reached.

Please feel free to contribute and improve/add functionalities
