# Billiards Tracker

Billiards Tracker is a stand-alone application that's single purpose is to keep track of multiple players while playing a game of said billiards.

## High-Level arch

Pretty simply, the interface will be written in PySide2, allowing for a selection of a few games including 8-ball, 3-man cutthroat, and 5-man cutthroat. Additionally, there will be a remote button to send a "turn finished" command to the application, advancing the current player. This communication will most likely arrive in the form of an API call.

## Hardware

A Raspberry Pi 3B+ will be running the host application (or any device capable of running a trusted python interpreter and has wireless network connectivity), and the remote device will be the same, but may need to be running on a battery, so little power consumption is important.

## Contributions

Anyone is more than welcome to contribute to the billiards tracker, please communicate over Discord what you want to work on, then feel free to create a new branch and start working.

### Installation

1. Download a Python interpreter, I recommend the reference implementation [cPython](https://www.python.org/downloads/release/python-379/).
2. Use [pip](https://pip.pypa.io/en/stable/installing/) or another package manager to get the requirements in `./requirements.txt`
   1. Download [get-pip.py](https://bootstrap.pypa.io/get-pip.py), run it with python and let it do the rest.
   2. Run `pip -r requirements.txt` to install all required packages.
3. Get coding!
