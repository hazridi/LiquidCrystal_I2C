# Installation #
Regular Arduino IDE:
Create a new folder called "LiquidCrystal_I2C" under the folder named "libraries" in your Arduino sketchbook folder.
Create the folder "libraries" in case it does not exist yet. Place all the files in the "LiquidCrystal_I2C" folder.

86Duino: place the LiquidCrystal_I2C folder in hardware/86duino/x86/libraries

# License #
This library is licensed under the GNU GPL version 2 or later.

# Usage #
To use the library in your own sketch, select it from *Sketch > Import Library*.

# Examples #
There are several types of I2C expander/backpack boards supported by this library. To find out which you have, I suggest
using an I2C scanner and finding the I2C address of the backpack, then trying each of the four HelloWorld sketches.
Sainsmart LCDs use the YWROBOT expander with an I2C address of 0x27 or sometimes 0x4E.

86Duino: There is a working 86Duino I2C scanner sketch available at http://github.com/hazridi/86duino_i2c_scanner

-------------------------------------------------------------------------------------------------------------------
This library is based on work done by DFROBOT, Sebastian Löser, and Frank de Brabander.
