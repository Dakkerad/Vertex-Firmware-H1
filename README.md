# Velleman Vertex Original (K8400) Single Extruder Firmware
![Github](https://img.shields.io/badge/license-GPL--3.0-orange)

Vertex firmware updated to Marlin 1.1.9!

This firmware is much newer than the one that Vellman provides for the Velleman Vertex Original (Velleman K8400)
The firmware includes new features such as bed leveling to compensate for an uneven print surface (which the K8400 is known for), and includes othe fixes and improvements included in newer Marlin firmwares to increase printing quality.

This firmware also includes other community fixes such as the E-steps fix, so you should use 100% Flow without overextrusion, and the preheat temperatures are adjusted to prevent/minimize clogging that are caused by the poor design of the original hotend.

I have tested this on my own "non hardware modified" Velleman K8400.

## Installation

*The installation is almost the same as the original Vertex Firmware*

0. Download the latest version of Arduino software if you havent already (This is a bonus by using the latest Marlin version, so you don't have to use the outdated 32-bit version of Arduino)
1. Clone this repository or just download it as a .zip file
2. Open the Marlin.ino file inside the Marlin folder
3.  Make sure the jumper on the printer is set ready to be flashed
4.  Make sure to choose the board "Arduino Board or Mega 2560" and make sure to choose the correct processor "ATMega 2560 (Mega 2560)" inside the Arduino software
5.  Make sure to choose the correct serial port
6.  Click the upload button on the software
7.  Wait until it is done and ignore the memory warning
8.  Open the menu, scroll to "Control", and scroll to "Initialize EEPROM"
9.  PROFIT??!1

## DISCLAIMER!

USE AT YOUR OWN RISK!

By using this firmware you agree to:

I will not be held responsible for any damage or harm done to you, your printer, people around you, or anything else in relation to the use/modification of this firmware.

## LICENSE

*Marlin is published under the GPL license because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.*

*While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.*

**Marlin Firmware**

*Same license as this modified firmware*

Website: https://marlinfw.org

Project: https://github.com/MarlinFirmware/Marlin

**Vertex Firmware**

*Same license as Marlin Firmware as the Vertex Firmware is based on this*

Website: https://vertex3dprinters.eu

Project: https://github.com/Velleman/Vertex-Firmware-H1
