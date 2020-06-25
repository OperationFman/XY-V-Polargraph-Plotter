# XY V Plotter Polargraph (Project: IPAD)
Interactive Programmable Arts Display - In partnership with the Ballarat Hackerspace

Team:
-Franklin Moon
-Zane Drysdale

This documentation will guide you through the installation of hardware AND software to DIY a Vertical Wall Printer for limitless scale with cheap and available parts.

Getting Started - Testing Hardware,

  Below are the instructions to setup and test the hardware (CNC shield, Arduino, Stepper Motors, Drivers and various connections.

    1. Plug in necessary hardware, uno on arduino, 12v to cnc, steppers to cnc etc (See wiring diagram)
    2. Download and install Arduino IDE https://www.arduino.cc/en/main/software
    3. Download GRBL https://github.com/gnea/grbl/releases
    4. Download XLoader http://www.hobbytronics.co.uk/arduino-xloader
    5. Follow instructions to get GRBL on the Arduino/cnc
    6. Download Universal Gcode Sender https://winder.github.io/ugs_website/
    7. UGS should detect the CNC shield and any connected motors
    8. Plug and Play Away
    
    
Setting up a Gamepad/Joystick   
  Below are the methods to using a joystick/gamepad or any analog input method.
 
    1. Plug in necessary component
    2. Download and install Joys2Key https://joytokey.net/en/
    3. Download the library file 'JoyToKeyToPlotter.cfg' file (In repo)
    4. Import file to JoyToKey
    4. From within UGS (Universal Gcode Sender), use the joystick 


Setting up WASD Input Method (Any Input Is Possible)
  Below are instructions to create live Gcode to be sent to the UGS Command Line, highly configurable
  
    1. Download and Install AutoHotkey https://www.autohotkey.com/
    2. Download library file 'GcodeWASD.ahk' file (In repo)
    3. Run the file (Manipulate as desired for alternate inputs)
    4. From within UGS Command Line, use WASD to initiate movement
