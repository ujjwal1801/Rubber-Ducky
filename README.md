#Disclaimer
This script has been shared for educational purposes. Any misuse of the script to harm any individual or system shall not make me responsible for the damage caused.

#USB Rubber Ducky

The USB Rubber Ducky is a keystroke injection tool disguised as a generic flash drive. Computers recognize it as a regular keyboard and accept pre-programmed keystroke payloads at over 1000 words per minute.

Payloads are crafted using a simple scripting language and can be used to drop reverse shells, inject binaries, brute force pin codes, and many other automated functions for the penetration tester and systems administrator.

#Ducky Script

Ducky Script is the language of the USB Rubber Ducky. Writing scripts for a rubber ducky can be done from any common ascii text editor such as Notepad, vi, emacs, nano, gedit, kedit, TextEdit, etc.

Ducky Script syntax is simple. Each command resides on a new line and may have options follow. Commands are written in ALL CAPS, because ducks are loud and like to quack with pride. Most commands invoke keystrokes, key-combos or strings of text, while some offer delays or pauses.

##This Script

This script uses a simple notepad bomb, which uses all the resources of the system, thus freezing it and rendering it unusable. The script places the notepad bomb in the startup folder, thus executing everytime the user boots up the account.

This script works only on Windows Operating System.

Credits: 
Ducky script - https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Duckyscript
Notepad bomb - http://www.theprohack.com/2009/02/simplest-virus-fork-bomb.html
