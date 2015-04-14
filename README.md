TinkerKit DMX Master Shield (rev4) with DMXSimple library
===================
Installation

0) Close Arduino IDE, unplug Arduino, unplug everything.
1) Download DMXSimple library
  - https://code.google.com/p/tinkerit/wiki/DmxSimple
2) Put extracted "DMXSimple" folder into ".../Documents/Arduino/libraries"
3) In ".../Documents/Arduino/libraries" open "DMXSimple.cpp" with a text editor. In line 11, change #include "wiring.h" to #include "Arduino.h" and save.
3) Run ArduinoIDE, plug in Arduino (with shield attached on top, and a stage light attached to the shield)
4) Oopen "example/DMXSimple/Fade UP" .. Compile, the stage light should fade from darkness to red.
