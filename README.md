Disclaimer
------------
DCC++ is an open-source hardware and software system for the operation of DCC-equipped model railroads.
It was originally developed under GPL 3.0 by DccPlusPlus and this is a link to the original branch.
https://github.com/DccPlusPlus/BaseStation

What’s DCC++
------------

DCC++ is an open-source hardware and software system for the operation of DCC-equipped model railroads.

The system consists of two parts, the DCC++ Base Station and the DCC++ Controller.

The DCC++ Base Station consists of an Arduino micro controller fitted with an Arduino Motor Shield that can be connected directly to the tracks of a model railroad.

The DCC++ Controller provides operators with a customizable GUI to control their model railroad.  It is written in Java using the Processing graphics library and IDE and communicates with the DCC++ Base Station via a standard serial connection over a USB cable or wireless over BlueTooth.

What’s in this Repository
-------------------------

This repository, BaseStationBT, contains a complete DCC++ Base Station sketch designed for compiling and uploading into an Arduino Mega.  All sketch files are in the folder named DCCpp_Uno. More information about the sketch can be found in the included PDF file.

To utilize this sketch, simply download a zip file of this repository and open the file DCCpp_Uno.ino within the DCCpp_Uno folder using your Arduino IDE.  Please do not rename the folder containing the sketch code, nor add any files to that folder.  The Arduino IDE relies on the structure and name of the folder to properly display and compile the code.

The latest production based on release of the Master branch is 1.2.1:

* Supports only Arduino Mega!
* Built-in configuration for both the original Arduino Motor Shield as well as a Pololu MC33926 Motor Shield
* Built-in configuration and support of Ethernet Shields (for use with Mega only)
* Support for HC05/HC06 bluetooth module on Serial1

For more information on the overall DCC++ system, please check the original project repository.
