# JellyKeypad
This project is based on the Arduino board : Pro Micro (Leonardo) 
It modifies a PC numeric keypad, replacing the existing controller with the Pro Micro.
This then offers 2 modes of operation, the first simply emulating the existing keypad functions, the second is activated by entering a pin within the first 30 seconds of power.
Once the correct pin has been entered, the keypad will transmit key sequences that are defined in user-strings.h
Each key of the keypad can store passwords, or other macro sequences, for example ssh login, or run a windows program with a single keypress.
Use of the NumLock key doubles the keys available. 
