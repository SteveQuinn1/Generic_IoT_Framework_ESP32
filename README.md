# Generic-ESP32-IoT-Framework

Generic ESP32 IoT Framework

This repository holds an example of a generic IoT device which can be used in conjunction with the Instructable series on home automation [here](https://www.instructables.com/id/Home-Automation-12/).
It has been successfully tested with the following devices; NodeMCU ESP-32S v1.1, WIMOS LOLIN32, TTGO, Heltek WIFI Kit, Core_Board_V2 

## Directory contents

### GenericIoTFrameWorkESP32_1

Contains the GenericIoTFrameWorkESP32_1.ino Arduino sketch along with the sub-directory 'data'

#### data

These files are to be copied to the device as SPIFFs and are used by the system at start up to configure the device and serve up a web page if the device cannot connect to your home network for whatever reason. 

There are two (main) text files named 'secvals.txt' and 'index.htm'

index.htm : This is the source of the 'Generic IoT Device Configuration Home Page'

secvals.txt : contains six entries used by the IoT device to connect to your home network. You will need to add your own SSID and P/W here.


