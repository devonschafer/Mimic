# Mimic
Mouse automation Program with Python3

Welcome to Mimic
This is a open source program built in python using guizero for the GUI.

What does Mimic do?
Mimic performs automated mouse movements for you after you record what you want to do.

I made this originally for game botting, but it can be used for whatever.

Current Mimic version is displayed on the title bar of the window.
For new versions go to:
https://github.com/devonschafer/Mimic_versions

I have slightly automated scripts in the respective folders for your OS version to help with the python
modules that are required.

Linux--------------------------------------------------------------------------
Linux is more supported since I use linux and perfer it. So you will see the linux .sh file has more
stuff in it.

Running the install_modules.sh by (go to directory where it lives, and in terminal)
sh install_modules.sh
This will upgrade pip if you already have python installed.
Install guizero, mouse, keyboard, and pyautogui modules.
Install git and install Mimic from github in the directory where you run this script.

If you run this program in Linux, you'll need to run it as sudo because I used python Mouse and Keyboard modules that require it.

example: (go to directory where Mimic lives) sudo python3 mimic.py

Windows--------------------------------------------------------------------------
I have automated the python modules process, but run after installing python3 because the script uses pip.
To run the script you'll need to Save As the install_pip.txt to install_pip.bat and double click it to run.
install_pip.bat will install guizero, mouse, keyboard, and pyautogui.

Double click on mimic.py to run
