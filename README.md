# ESP32 - collection 

This repo contains ESP32 (example) programs.
Currently only Arduino v2 IDE is used to build and upload the code to the devices, using an USB connector.

Check  [T-Display-S3 repo](https://github.com/Xinyuan-LilyGO/T-Display-S3) how to setup Arduino environment for the T-Display S3 PRO.




# Projects

Projects in next folders explained:

| Name | Info to original repo | description | 
| ----------------- | ----- | -------- | 
| TPro | clone of [VolosR](https://github.com/VolosR/TPro) | T-Display S3 - Pro example |
| TPro_Vinz | update of [VolosR](https://github.com/VolosR/TPro) | T-Display S3 - Pro Example, with Extra Debug info via Serial Monitor |
| WifiClientConnect | Arduino Example | Connect to Wifi and report status |

## How to Use Example

* How to install the Arduino IDE: [Install Arduino IDE](https://github.com/espressif/arduino-esp32/tree/master/docs/arduino-ide).

#### Using Arduino IDE

* Before Compile/Verify, select the correct board: `Tools -> Board`.
* Select the COM port: `Tools -> Port: xxx` where the `xxx` is the detected COM port.

#### Using Platform IO

* Select the COM port: `Devices` or set the `upload_port`` option on the `platformio.ini` file.


## Troubleshooting

***Important: Be sure you're using a good quality USB cable that has enough power for your project.***

* **Programming Fail:** If the programming/flash procedure fails, try to reduce the serial connection speed.
* **COM port not detected:** Check the USB cable connection and the USB to Serial driver installation.

If the error persists, you can ask for help at the official [ESP32 forum](https://esp32.com) or see [Contribute](#contribute).



## Resources

* Arduino-ESP32 Official Repository: [espressif/arduino-esp32](https://github.com/espressif/arduino-esp32)
* ESP32 Datasheet: [Link to datasheet](https://www.espressif.com/sites/default/files/documentation/esp32_datasheet_en.pdf)
* ESP32-S2 Datasheet: [Link to datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-s2_datasheet_en.pdf)
* ESP32-C3 Datasheet: [Link to datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-c3_datasheet_en.pdf)
* Official ESP-IDF documentation: [ESP-IDF](https://idf.espressif.com)
* T-Display-S3 repo (https://github.com/Xinyuan-LilyGO/T-Display-S3)
