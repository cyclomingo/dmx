
Arduino Uno+TinkerKit DMX Master Shield(rev4)+DMXSimple library
===================
 Installation
------------------
> - Close Arduino IDE, unplug Arduino, unplug everything.
> - Download DMXSimple library
  - https://code.google.com/p/tinkerit/wiki/DmxSimple
> - Put extracted "DMXSimple" folder into ".../Documents/Arduino/libraries"
> - In ".../Documents/Arduino/libraries" open "DMXSimple.cpp" with a text editor. In line 11, change #include "wiring.h" to #include "Arduino.h" and save.
> - Run ArduinoIDE, plug in Arduino (with shield attached on top, and a stage light attached to the shield)
> - Open "example/DMXSimple/Fade UP" .. Compile, the stage light should fade from darkness to red.
