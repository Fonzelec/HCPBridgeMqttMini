# Hörmann mini HCPBridge with MQTT and HomeAssistant Support

The aim of this project is to control a Hörmann garage door over wifi.

* Hardware development was made by myself. Gerber files and BOM are available to download so you can build your own.
The PCB doesn't embed any onboard sensor.
Soldering iron + assembly tools are needed to assemble a board.
If you are looking for an assembled PCB or a device, I still have some material left --> message me.

* Software was forked from [HCPBridgeMqtt](https://github.com/Gifford47/HCPBridgeMqtt).
You'll need a FTDI TTL-232R-3V3 or compatible cable + external power supply (5-24 VDC / 2.5 W) to flash the embedded ESP32 MCU.

It is tested and currently works on a SupraMatic 4 door controller, but should also support other models (see forked project readme). As it is small enough, it fits in the accessory compartment of the controller.

If you find this useful, please feel free to [donate](https://ko-fi.com/fonzelec) and support my work !
