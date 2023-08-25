# keylogger
Keylogger written in python for windows and linux both.
Windows-Keylogger python3

#Python Keylogger for Windows
A Keylogger for Windows implemented using PyHook and Pythoncom modules.

Usage
Clone or download the repository. Open a Powershell or Command Prompt Terminal in the directory of the repository.
Run python3 keylog.py.
The keylogger will start taking input from the keyboard and storing the keystrokes in the output.txt file in the same directory.
Press Ctrl + E or close the terminal window to stop the keylogger.

#Linux-Keylogger  python3
- git clone https://github.com/nandydark/Linux-keylogger.git
- cd Linux-keylogger
- sudo apt-get install python-xlib
- pip install pyxhook
- python main.py

import os
import pyxhook
