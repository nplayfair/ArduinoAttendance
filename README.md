# Arduino Attendance Monitor

This is a reimplementation of the project I did at university to use RFID tags as a way of logging attendance at an event, such as a lecture. I originally wrote it in C# and used an MS Access database to store the logs but this project will eventually use node and a more robust database.

## Requirements

* Arduino or compatible microcontroller board such as a Nano
* RFID module. I developed this with a generic RFID-RC522 board. Should work with any module compatible with [Miguel Balboa's rfid library](https://github.com/miguelbalboa/rfid)
* Platformio will handle library management etc

## Dependencies

* **Arduino.h**

  * From: Arduino IDE / target specific
  * License: (target: Arduino) GNU Lesser General Public License 2.1

* **SPI.h**

  * From: Arduino IDE / target specific
  * License: (target: Arduino) GNU Lesser General Public License 2.1

* **stdint.h**

  * From: Arduino IDE / Compiler and target specific
  * License: different

* **MFRC522.h**
  * From: [rfid](https://github.com/miguelbalboa/rfid)

  * License: Unlicense

## Addendum

Original project by [nplayfair](http://twitter.com/nplayfair)
