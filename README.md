## Syringe Pump

You can find here:
- Arduino code which has to be uploaded to the microcontroller "Arduino Nano BLE 33". This code enables communication between the Trinamic stepper drivers and your personal computer
- PyQT5 code for the Syringe Pump app that is running on the personal comupter enables direct control over the pump via a garaphical user interface

Graphical user interface of the Syringe Pump app:

![Syringe pump GUI logo](https://raw.githubusercontent.com/BastianWagner/Syringe_Pump/master/Syringe_pump_GUI_1.png)


GUI was coded in python with PyQt5:

PyQt5 has to be installed on MAC with the terminal command...
> pip install PyQt5


Syringe Pump Setup with microcontroller board:

![Syringe pump setup logo](https://raw.githubusercontent.com/BastianWagner/Syringe_Pump/master/Syringe_pump.png)


-----------------------------------------------Dark mode notes----------------------------------------- <br>
BreezeStyleSheets:
https://github.com/Alexhuszagh/BreezeStyleSheets

Folder:
- dark 
- light

Files:
- dark.qss
- light.qss
- breeze_resources.py
- breeze.qrc

To compile the stylesheet for use with PyQt5, compile with the following command...
> pyrcc5 breeze.qrc -o breeze_resources.py <br>

----------------------------------------------------------------------------------------------------




-----------------------------------------------OSX Application-------------------------------------- <br> 
Py2app:
py2app is a Python setuptools command which will allow you to make standalone Mac OS X application bundles and plugins from Python scripts.
NOTE: py2app must be used on OSX to build applications, it cannot create Mac applications on other platforms.

py2app can be installed with the comand...
> pip3 install py2app

Folder:
- dist
- build

File:
- setup.py
- icon.icns

To build app use following comand...
> python setup.py py2app


---------------------------------------------------------------------------------------------------- <br> 


