# ESP8266-D1-Wifi-UNO-China-connecting-to-MP3-TF-16F
ESP8266 D1 Wifi UNO from China connecting to MP3-TF-16F

## Requirements
You have to install Arduino IDE 1.6.10 or later. Links are listed below.
* **Arduino** > **Preferences** > "Additional Boards Manager URLs:" and add: **http://arduino.esp8266.com/stable/package_esp8266com_index.json**
* **Arduino** > **Tools** > **Board** > **Boards Manager** > type in **ESP8266** and install the board
* Download MFRC522 library and extract to Arduino library folder or you can use "Library Manager" on the IDE itself to install the MFRC522 library.

### Download Links
* [Arduino IDE](https://www.arduino.cc/en/Main/Software) - The development IDE
* [ESP8266 Core for Arduino IDE](https://github.com/esp8266/Arduino) - ESP8266 Core
* [MFRC522 Library](https://github.com/miguelbalboa/rfid) - MFRC522 RFID Library

###Arduino IDE Settings
*Version: 1.8.19
*Board: NodeMDU 1.0 (ESP12-E Module)
*Upload Speed: 115200
*Port: /ty0/USB0

## Simple Example

### Wiring RFID RC522 module
The following table shows the typical pin layout used:

| Signal        | MFRC522       |Wemos D1 Wifi Uno | Generic      |
|---------------|:-------------:|:----------------:|:------------:|
| TX0           | TX            | D11 [1]          | GPIO-13 [1]  |
| RX1           | RX            | D10 [1]          | GPIO-15 [2]  |
